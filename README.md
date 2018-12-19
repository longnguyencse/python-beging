# Example Package

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.
https://techtalk.vn/blog/posts/python-test-python-don-gian-nhu-giat-mot-soi-tox

Các bước phải làm:

đầu tiên là tạo virtualenv
rồi source virtualenv
chạy pip install -r requirements.txt
chạy flake8 kiểm tra lỗi pep-0008
chạy pylint kiểm tra lỗi lint 
install module (python setup.py install) rồi chạy test
chạy test bằng py.test tests/ hoặc một cách nào đó khác
public package nếu test thành công (python setup.py sdist)
dọn dẹp, rửa ráy sau khi xong xuôi.


pip install -r requirements.txt
https://techtalk.vn/blog/posts/python-test-python-don-gian-nhu-giat-mot-soi-tox

setup(
    name="MyLibrary",
    version="1.0",
    install_requires=[
        "requests",
        "bcrypt",
    ],
    # ...
)

https://caremad.io/posts/2013/07/setup-vs-requirement/

pip install -r requirements.txt
