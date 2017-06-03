sentry_logger
-------------

To use (with caution), simply do::


    >>> pip3 install sentry-logger

    >>> from sentry_logger import SentryLogger
    >>> test_dsn = 'SENTRY_DSN'
    >>> class TestClass(object):
    >>> @SentryLogger(test_dsn)
    >>> def test_func(self):
    >>>    ...
