# Example Package

This is a simple example package. You can use <br />
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.  <br />
https://techtalk.vn/blog/posts/python-test-python-don-gian-nhu-giat-mot-soi-tox

Các bước phải làm: <br />

đầu tiên là tạo virtualenv <br />
rồi source virtualenv <br />
chạy pip install -r requirements.txt <br />
chạy flake8 kiểm tra lỗi pep-0008 <br />
chạy pylint kiểm tra lỗi lint  <br />
install module (python setup.py install) rồi chạy test <br />
chạy test bằng py.test tests/ hoặc một cách nào đó khác <br />
public package nếu test thành công (python setup.py sdist) <br />


pip install -r requirements.txt <br />
https://techtalk.vn/blog/posts/python-test-python-don-gian-nhu-giat-mot-soi-tox
 <br />
setup(
    name="MyLibrary",
    version="1.0",
    install_requires=[
        "requests",
        "bcrypt",
    ],
    # ...
)
 <br />
https://caremad.io/posts/2013/07/setup-vs-requirement/
 <br />
pip install -r requirements.txt
