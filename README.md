<h1>Python_img</h1>

<h2>Dockerfile</h2>
From python:3.10-slim
copy . /
cmd ["python", "python.py"]

<h2>python.py</h2>
print("Hello, world!")
