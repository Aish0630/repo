def add(a, b):
    return a + b

if __name__ == "__main__":
    print("Hello, CI/CD!")
from app import add

def test_add():
    assert add(2, 3) == 5
