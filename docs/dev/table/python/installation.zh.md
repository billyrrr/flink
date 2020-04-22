---
title: "环境安装"
nav-parent_id: python_tableapi
nav-pos: 10
---
<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

* This will be replaced by the TOC
{:toc}

## 环境要求
<span class="label label-info">Note</span> PyFlink需要Python版本3.5、3.6或3.7。 请运行以下命令以确保其符合要求：

{% highlight bash %}
$ python --version
# 此处显示的版本必须为3.5、3.6或3.7
{% endhighlight %}

## 安装PyFlink

PyFlink已经部署到PyPi，可以按以下方式安装：

{% highlight bash %}
$ python -m pip install apache-flink
{% endhighlight %}

您还可以按照[开发指南]({{ site.baseurl }}/zh/flinkDev/building.html#build-pyflink)从源代码构建PyFlink。
