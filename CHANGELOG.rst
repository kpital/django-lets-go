Changelog
=========
2.9.7 (2024-04-05)
------------------

* Change use ugettext_lazy to gettext_lazy

2.9.6 (2017-01-23)
------------------

* Add a page size parameter to `get_pagination_vars`


2.9.5 (2015-12-14)
------------------

* Choice get_value is not a classmethod


2.9.4 (2015-12-11)
------------------

* django SortedDict deprecated replace by OrderedDict


2.9.3 (2014-09-23)
------------------

* use ugettext_lazy


2.9.2 (2014-03-10)
------------------

* update function ceil_strdate


2.9.1 (2014-02-06)
------------------

* fix common_tags import error


2.9.0 (2014-02-05)
------------------

* rename project to django-lets-go


2.8.5 (2014-01-30)
------------------

* new template tag ``word_capital`` -  Capitalizes the first character of each word


2.8.4 (2014-01-23)
------------------

* new template tag ``percentage`` - Get percentage value


2.8.3 (2013-12-28)
------------------

* new template filter wordcap - Capitalizes the first character of each words.


2.8.2 (2013-12-09)
------------------

* Support for Django 1.6


2.8.1 (2013-06-03)
------------------

* Add setting to ceil_strdate - hour_min support hours and minutes


2.8.0 (2013-06-03)
------------------

* Add constant EXPORT_CHOICE - Define list of format to export
* Add class HorizRadioRenderer - This overrides widget method to put
    radio buttons horizontally instead of vertically.


2.7.2 (2013-05-13)
------------------

* new function unset_session_var : Unset session variables


2.7.1 (2013-05-13)
------------------

* new function getvar(request, field_name, setsession=False)
    Check field in POST/GET request and return field value
    if there is value you can also save a session variable


2.7.0 (2013-05-02)
------------------

* add percentage function - Get percentage value


2.6.0 (2013-02-22)
------------------

* Add export_as_csv_action - Admin custom action which returns an export csv


2.5.0 (2013-02-21)
------------------

* Add new AppLabelRenamer - Rename app label and app breadcrumbs in admin


2.4.1 (2013-02-10)
------------------

* Decorator only_one for celery can define the key from the calling method


2.4.0 (2012-11-30)
------------------

* Add BigIntegerField - Field to provide BigInt for Mysql and PostgreSQL
* PEP Fixes


2.3.0 (2012-11-23)
------------------

* Pagination function - get_pagination_vars


2.2.3 (2012-10-26)
------------------

* LanguageField - Field to language list


2.2.2 (2012-10-25)
------------------

* convert_to_int - New template tag


2.2.1 (2012-10-24)
------------------

* get_unique_code - Generate unique code


2.2.0 (2012-10-23)
------------------

* add ceil_strdate function - Convert a string date to either a start or end day date


2.1.3 (2012-10-19)
------------------

* rename function mongodb_collection_duration_filter to mongodb_int_filter
* rename mongodb_collection_filter to mongodb_str_filter


2.1.0 (2012-10-04)
------------------

* Import project to Pypi
