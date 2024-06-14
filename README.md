[tool.poetry]
name = "py_canalyzer"
version = "0.0.1"
description = "Python CANalyser Package"
description = "Python CANalyzer Package"
authors = ["chaitu-ycr <chaitu.ycr@gmail.com>"]
license = "LICENSE"
readme = "README.md"
homepage = "https://github.com/chaitu-ycr/py_canalyzer.git"
repository = "https://github.com/chaitu-ycr/py_canalyzer.git"
documentation = "https://chaitu-ycr.github.io/py_canalyzer/"
keywords = ["Vector", "CANalyser", "py_canalyzer"]
keywords = ["Vector", "CANalyzer", "py_canalyzer"]
classifiers = [
    "Programming Language :: Python :: 3.9",
    "License :: OSI Approved :: MIT License",
@@ -18,6 +18,7 @@ classifiers = [
packages = [
    { include = "py_canalyzer.py", from = "src" },
    { include = "py_canalyzer_utils/*.py", from = "src"},
    { include = "py_canalyzer_utils/app_utils/*.py", from = "src"},
]

[tool.poetry.dependencies]
