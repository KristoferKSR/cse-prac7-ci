# cse-prac7-ci
[![Build Status](https://travis-ci.com/KristoferKSR/cse-prac7-ci.svg?branch=master)](https://travis-ci.com/KristoferKSR/cse-prac7-ci)

Kristofer Käosaar@DESKTOP-MT4TVVH MINGW64 ~/Desktop/EZEAP/cse-prac7-ci (master)
$ git commit
============================= test session starts =============================
platform win32 -- Python 3.7.1, pytest-3.2.1, py-1.4.34, pluggy-0.4.0
rootdir: C:\Users\Kristofer Käosaar\Desktop\EZEAP\cse-prac7-ci, inifile:
collected 1 item

test_sample.py F

================================== FAILURES ===================================
_________________________________ test_answer _________________________________

    def test_answer():
>       assert inc(3) == 5
E       assert 4 == 5
E        +  where 4 = inc(3)

test_sample.py:5: AssertionError
========================== 1 failed in 0.06 seconds ===========================

$ git commit
============================= test session starts =============================
platform win32 -- Python 3.7.1, pytest-3.2.1, py-1.4.34, pluggy-0.4.0
rootdir: C:\Users\Kristofer Käosaar\Desktop\EZEAP\cse-prac7-ci, inifile:
collected 1 item

test_sample.py .

========================== 1 passed in 0.03 seconds ===========================
[master 1a20938] finished practice
 2 files changed, 23 insertions(+), 1 deletion(-)
