# coding=utf-8
# Copyright 2014 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_library(
  name = 'all',
  dependencies = [
    ':android',
  ],
)

python_library(
  name = 'android',
  sources = [
    'android_binary.py',
    'android_dependency.py',
    'android_library.py',
    'android_resources.py',
    'android_target.py',
  ],
  dependencies = [
    'src/python/pants/backend/jvm/targets:jvm',
    'src/python/pants/base:build_environment',
    'src/python/pants/base:exceptions',
    'src/python/pants/base:payload',
    'src/python/pants/base:payload_field',
    'src/python/pants/base:target',
    'src/python/pants/backend/android:android_manifest_parser',
    'src/python/pants/backend/core/targets:common',
    'src/python/pants/util:memo',
  ],
)
