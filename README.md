<p align="center"><a href="https://dataease.io"><img src="https://dataease.oss-cn-hangzhou.aliyuncs.com/img/dataease-logo.png " alt="DataEase" width="300" /></a></p> <h3 align="center">Open source BI tools for everyone</h3> <p align="center"> <a href="https://www.gnu.org/licenses/gpl-3.0.html"><img src="https://img.shields.io/github/license/dataease/dataease?color=% 231890FF" alt="License: GPL v3"></a> <a href="https://app.codacy.com/gh/dataease/dataease?utm_source=github.com&utm_medium=referral&utm_content=dataease/dataease&utm_campaign=Badge_Grade_Dashboard"><img src="https://app.codacy.com/project/badge/Grade/da67574fd82b473992781d1386b937ef" alt="Codacy"></a> <a href="https://github.com/dataease/dataease"><img src="https://img.shields.io/github/stars/dataease/dataease?color=%231890FF&style=flat-square" alt="GitHub Stars"></a> <a href="https://gitee.com/fit2cloud-feizhiyun/DataEase"><img src="https://gitee.com/fit2cloud-feizhiyun/DataEase/badge/star.svg?theme=gvp" alt=" Gitee Stars"></a><br>
[<a href="/README.md">Chinese (Simplified)</a>] | [<a href="/README_EN.md">English</a> ]
</p>

------------------------------

## What is DataEase?

DataEase is an open source BI tool that helps users Quickly analyze data and gain insights into business trends to improve and optimize your business. DataEase supports a wide range of data source connections, can quickly create charts by dragging and dropping, and can be easily shared with others.

**Advantages of DataEase:**

- Open source: zero threshold, quick online acquisition and installation, monthly iteration;
- Easy to use: extremely easy to use, analysis can be completed by clicking and dragging the mouse;
- Full scene support : Multi-platform installation and diversified embedding support;
- Secure sharing: Supports multiple data sharing methods to ensure data security.

**Data sources supported by DataEase:**

- OLTP databases: MySQL, Oracle, SQL Server, PostgreSQL, MariaDB, Db2, TiDB, MongoDB-BI, etc.;
- OLAP database: ClickHouse, Apache Doris, Apache Impala, StarRocks, etc.;
- Data warehouse/data lake: Amazon RedShift, etc.;
- Data file: Excel, CSV, etc.;
- API data source.

If you need to introduce DataEase to your team, you can use this [official PPT material](https://fit2cloud.com/dataease/download/introduce-dataease_202411.pdf).

## Quick Start```
# Prepare a 2-core 4G The above Linux server, and run the following one-click installation script as root user:

curl -sSL https://dataease.oss-cn-hangzhou.aliyuncs.com/quick_start_v2.sh | bash

# Username: admin
# Password: DataEase@ 123456
```

You can also quickly deploy DataEase through the [1Panel App Store](https://dataease.io/docs/v2/installation/1panel_installation/).

If it is used in a production environment, it is recommended to use the [offline installation package method](https://dataease.io/docs/v2/installation/offline_INSTL_and_UPG/) for installation and deployment.

If you have more questions, you can check the online documentation, or Communicate with us via the forum.

- [Online Experience](https://dataease.io/demo.html)
- [Online Documentation](https://dataease.io/docs/)
- [Community Forum](https://bbs.fit2cloud.com /c/de/6)
- [Getting Started Video](https://www.bilibili.com/video/BV1Z84y1X7eF/)
- [Template Market](https://templates.dataease.cn/)

## UI Display< table style="border-collapse: collapse; border: 1px solid black;">
<tr>
<td style="padding: 5px;background-color:#fff;"><img src= "https://github. com/dataease/dataease/assets/41712985/8dbed4e1-39f0-4392-aa8c-d1fd83ba42eb" alt="DataEase Workbench" /></td>
<td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/dataease/dataease/assets/41712985/7c54cb07- 51ef-4bb6-a931-8a95c64c7e11" alt="DataEase Dashboard" /></td>
</tr>

<tr>
<td style="padding: 5px;background-color:#fff;"><img src= "https://github.com/dataease/dataease/assets/41712985/ffa79361-a7b3-4486-b14a-f3fd3a28f01a" alt="DataEase Data Source" /></td>
<td style="padding: 5px;background-color:#fff;"><img src="https://github.com/dataease/dataease/assets/41712985/bb28f4e4-636e-4ab0-85c5-1dfbd7a5397e" alt="DataEase Template Center" / ></td>
</tr>
</table>

## Technology stack - front-end: [Vue.js](https://vuejs.org/), [Element](https://element.eleme.cn/ )
- Gallery: [AntV](https://antv.vision/zh)
- Backend: [Spring Boot](https://spring.io/projects/spring-boot)
- Database: [MySQL](https: //www.mysql.com/)
- Data processing: [Apache Calcite](https://github.com/apache/calcite/), [Apache SeaTunnel](https://github.com/apache/seatunnel)
- Infrastructure: [Docker](https://www.docker.com/)
## Other star projects of Feizhiyun - [1Panel](https: //github.com/1panel-dev/1panel/) - Modern, open source Linux server operation and maintenance management panel - [MaxKB](https://github.com/1panel-dev/MaxKB/) - Based on LLM large language model The open source knowledge base question-answering system - [JumpServer](https://github.com/jumpserver/jumpserver/) - The popular open source bastion host - [Halo](https://github.com/halo-dev/halo /) - Powerful and easy-to-use open source website building tool - [MeterSphere](https://github.com/metersphere/metersphere/) - A new generation of open source continuous testing tools## License

Copyright (c) 2014-2024 [FIT2CLOUD Feizhiyun](https://fit2cloud.com/), All rights reserved. Licensed under The GNU General Public License version 3 (GPLv3) (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at <https://www.gnu.org/licenses/gpl-3.0.html> Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
