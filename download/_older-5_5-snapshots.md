{% if xcode_5_5_builds.size > 1 %}

Xcode
<table id="osx-builds" class="downloads">
    <thead>
        <tr>
            <th class="download">Download</th>
        </tr>
    </thead>
    <tbody>
        {% for build in xcode_5_5_builds | offset:1 | limit:10 %}
            {% include_relative _old-snapshot.html build=build name="Xcode" platform_dir="xcode" branch_dir="swift-5.5-branch" %}
        {% endfor %}
    </tbody>
</table>

{% endif %}

{% if ubuntu1604_5_5_builds.size > 1 %}

Ubuntu 16.04

<table id="linux-builds" class="downloads">
    <thead>
        <tr>
            <th class="download">Download</th>
        </tr>
    </thead>
    <tbody>
        {% for build in ubuntu1604_5_5_builds | offset:1 | limit:10 %}
            {% include_relative _old-snapshot.html build=build name="Ubuntu 16.04" platform_dir="ubuntu1604" branch_dir="swift-5.5-branch" %}
        {% endfor %}
    </tbody>
</table>

{% endif %}


{% if ubuntu1804_5_5_builds.size > 1 %}

Ubuntu 18.04

<table id="linux-builds" class="downloads">
    <thead>
        <tr>
            <th class="download">Download</th>
        </tr>
    </thead>
    <tbody>
        {% for build in ubuntu1804_5_5_builds | offset:1 | limit:10 %}
            {% include_relative _old-snapshot.html build=build name="Ubuntu 18.04" platform_dir="ubuntu1804" branch_dir="swift-5.5-branch" %}
        {% endfor %}
    </tbody>
</table>

{% endif %}

{% if ubuntu2004_5_5_builds.size > 1 %}

Ubuntu 20.04

<table id="linux-builds" class="downloads">
    <thead>
        <tr>
            <th class="download">Download</th>
        </tr>
    </thead>
    <tbody>
        {% for build in ubuntu2004_5_5_builds | offset:1 | limit:10 %}
            {% include_relative _old-snapshot.html build=build name="Ubuntu 20.04" platform_dir="ubuntu2004" branch_dir="swift-5.5-branch" %}
        {% endfor %}
    </tbody>
</table>

{% endif %}

{% if centos7_5_5_builds.size > 1 %}

CentOS 7

<table id="linux-builds" class="downloads">
    <thead>
        <tr>
            <th class="download">Download</th>
        </tr>
    </thead>
    <tbody>
        {% for build in centos7_5_5_builds | offset:1 | limit:10 %}
            {% include_relative _old-snapshot.html build=build name="CentOS 7" platform_dir="centos7" branch_dir="swift-5.5-branch" %}
        {% endfor %}
    </tbody>
</table>

{% endif %}

{% if centos8_5_5_builds.size > 1 %}

CentOS 8

<table id="linux-builds" class="downloads">
    <thead>
        <tr>
            <th class="download">Download</th>
        </tr>
    </thead>
    <tbody>
        {% for build in centos8_5_5_builds | offset:1 | limit:10 %}
            {% include_relative _old-snapshot.html build=build name="CentOS 8" platform_dir="centos8" branch_dir="swift-5.5-branch" %}
        {% endfor %}
    </tbody>
</table>

{% endif %}

{% if amazonlinux2_5_5_builds.size > 1 %}

Amazon Linux 2

<table id="linux-builds" class="downloads">
    <thead>
        <tr>
            <th class="download">Download</th>
        </tr>
    </thead>
    <tbody>
        {% for build in amazonlinux2_5_5_builds | offset:1 | limit:10 %}
            {% include_relative _old-snapshot.html build=build name="Amazon Linux 2" platform_dir="amazonlinux2" branch_dir="swift-5.5-branch" %}
        {% endfor %}
    </tbody>
</table>

{% endif %}

{% if windows10_5_5_builds.size > 1 %}

Windows 10

<table id="linux-builds" class="downloads">
    <thead>
        <tr>
            <th class="download">Download</th>
        </tr>
    </thead>
    <tbody>
        {% for build in windows10_5_5_builds | offset:1 | limit:10 %}
            {% include_relative _old-snapshot.html build=build name="Windows 10" platform_dir="windows10" branch_dir="swift-5.5-branch" %}
        {% endfor %}
    </tbody>
</table>

{% endif %}
