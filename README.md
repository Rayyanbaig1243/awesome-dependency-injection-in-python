# Awesome Dependency Injection in Python

> A curated list of awesome things related to dependency inversion / dependency injection in Python.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


## Talks / slides

- **Python Dependency Injection** [(PDF)](http://www.aleax.it/yt_pydi.pdf) (Alex Martelli, 2008).
- Fang: Pythonic dependency injection [(video)](https://www.youtube.com/watch?v=zqRd941NXlI&t=443s) (Nathan Craike, 2015).

## Videos

- [Loose Coupling & Dependency Injection the EASY Way!](https://www.youtube.com/watch?v=uWTvMCra-_Y) (Hynek Schlawack, 2024)
- [Dependency Inversion: Write BETTER PYTHON CODE Part 2]([https://www.youtube.com/watch?v=2ejbLVkCndI](https://www.youtube.com/watch?v=Kv5jhbSkqLE)) (ArjanCodes, 2021)
- [Dependency INVERSION vs Dependency INJECTION in Python](https://www.youtube.com/watch?v=2ejbLVkCndI) (ArjanCodes, 2021)


## Articles / blog posts

- [Enforcing Single Responsibility Principle in Python](https://sobolevn.me/2019/03/enforcing-srp) (Nikita Sobolev / Никита Соболев, 2019)
- [Pythonic Dependency Injection: A Practical Guide](https://medium.com/@suneandreasdybrodebel/pythonic-dependency-injection-a-practical-guide-83a1b1299280) (Sune Andreas Dybro Debel, 2018)
- [Elegant Flask API Development Part 1](https://christophergs.github.io/python/2018/09/25/elegant-flask-apis-pt-1/) (mostly covers Flask-Injector).
- ["(pytest) Fixtures: a prime example of dependency injection"](https://docs.pytest.org/en/latest/fixture.html#fixtures-a-prime-example-of-dependency-injection)
- [Tests and comparison of Python dependency injection libraries ★3](https://github.com/orsinium/dependency_injectors) - Tests and comparison of Python dependency injection libraries. [🐍, Unknown license].
- [Typed Functional Dependency Injection in Python](https://sobolevn.me/2020/02/typed-functional-dependency-injection)
- [DI patterns](https://lab.abilian.com/Tech/Architecture%20%26%20Design/Dependency%20Inversion/DI%20patterns/) (Abilian, 2024)
- [DI anti-patterns](https://lab.abilian.com/Tech/Architecture%20%26%20Design/Dependency%20Inversion/DI%20anti-patterns/) (Abilian, 2024)


## Books

- [Pythonic Application Architecture Patterns for Managing Complexity ★3371](https://github.com/python-leap/book) - A Book about Pythonic Application Architecture Patterns for Managing Complexity.  Cosmos is the Opposite of Chaos you see. O'R. wouldn't actually let us call it "Cosmic Python" tho. [🐍, Other license].


## Software

### DI Frameworks / Containers

- [python-dependency-injector ★3871](https://github.com/ets-labs/python-dependency-injector) - Dependency injection framework for Python. [🐍, BSD 3-Clause "New" or "Revised" License].
- [returns ★3499](https://github.com/dry-python/returns) - Make your functions return something meaningful, typed, and safe!. [🐍, BSD 2-Clause "Simplified" License].
- [Injector ★1299](https://github.com/alecthomas/injector) - Python dependency injection framework, inspired by Guice. [🐍, BSD 3-Clause "New" or "Revised" License].
- [Inject ★694](https://github.com/ivankorobkov/python-inject) - Python dependency injection. [🐍, Apache License 2.0].
- [Kink ★402](https://github.com/kodemore/kink) - Dependency injection container made for Python. [🐍, MIT License].
- [Dependencies ★360](https://github.com/proofit404/dependencies) - Constructor injection designed with OOP in mind. [🐍, BSD 2-Clause "Simplified" License].
- [Dishka ★384](https://github.com/reagento/dishka) - Cute DI framework with agreeable API and everything you need. [🐍, Apache License 2.0].
- [Punq ★303](https://github.com/bobthemighty/punq) - An IoC container for Python 3.6+. [🐍, MIT License].
- [di ★297](https://github.com/adriangb/di) - Pythonic dependency injection. [🐍, MIT License].
- [svcs ★289](https://github.com/hynek/svcs) - A Flexible Service Locator for Python. [🐍, MIT License].
- [FastDepends ★293](https://github.com/lancetnik/FastDepends) - FastAPI Dependency Injection system extracted from FastAPI and cleared of all HTTP logic. [🐍, MIT License].
- [Lagom](https://lagom-di.readthedocs.io/en/latest/) ★246: Type based auto-wiring dependency injection with support for async and threading. [🐍, MIT License].
- [Rodi ★176](https://github.com/RobertoPrevato/rodi) - Implementation of dependency injection for Python 3. [🐍, MIT License].
- [That Depends ★137](https://github.com/modern-python/that-depends) - simple DI-framework, inspired by python-dependency-injector, but without wiring [🐍, MIT License].
- [injectable ★112](https://github.com/allrod5/injectable) - Python Dependency Injection for Humans™. [🐍, MIT License].
- [Wireup ★93](https://github.com/maldoinc/wireup) - Concise, Powerful, and Type-Safe Python Dependency Injection Library. [🐍, MIT License].
- [Opyoid ★64](https://github.com/illuin-tech/opyoid) - Dependency injection library for Python. [🐍, MIT License].
- [Fresh Bakery ★21](https://github.com/Mityuha/fresh-bakery) - Bake dependency injections asynchronously and stupidly simple. [🐍, MIT License].
- [andi ★20](https://github.com/scrapinghub/andi) - Library for annotation-based dependency injection. [🐍, BSD 3-Clause "New" or "Revised" License].
- [Picodi ★20](https://github.com/yakimka/picodi) - A DI library inspired by FastAPI. It integrates well with FastAPI but can also be used independently. [🐍, MIT License].
- [Clean IoC ★9](https://github.com/peter-daly/clean_ioc) - A simple unintrusive dependency injection library for python with strong support for generics [🐍, MIT License].
- [injection ★5](https://github.com/nightblure/injection) - replacement for [python-dependency-injector](https://github.com/ets-labs/python-dependency-injector) that works with Python 3.8-3.12 and works with FastAPI, DRF, Flask and Litestar [🐍, MIT License].

### DI components of Web frameworks

Several modern Python web frameworks include DI components, including:

- FastAPI -> [Dependencies - First Steps](https://fastapi.tiangolo.com/tutorial/dependencies/).
- Litestar -> [Dependency Injection](https://docs.litestar.dev/2/usage/dependency-injection.html).
- Sanic -> [Dependency Injection](https://sanic.dev/en/plugins/sanic-ext/injection.html).
- Xpresso -> [di](https://github.com/adriangb/di) (see above)
- Blacksheep -> [Rodi](https://github.com/RobertoPrevato/rodi) (see above)
- Aiodine (dead, see below) was the DI framework for the Bocadillo project (also dead)


### Archived or unmaintained DI frameworks

- [Antidote ★90](https://github.com/Finistere/antidote) - Dependency injection for Python. [🐍, MIT License].
- [Serum ★85](https://github.com/suned/serum) - Dependency injection framework for Python 3.6. [🐍, MIT License].
- [Aiodine ★53](https://github.com/bocadilloproject/aiodine) - 🧪 Async-first Python dependency injection library. [🐍, MIT License].
- [Wiring ★26](https://github.com/msiedlarek/wiring) - Architectural foundation for Python applications. [🐍, Apache License 2.0].


### Integration with web frameworks

- [Flask-Injector ★275](https://github.com/alecthomas/flask_injector) - Adds Injector support to Flask. [🐍, BSD 3-Clause "New" or "Revised" License].

See also above.
