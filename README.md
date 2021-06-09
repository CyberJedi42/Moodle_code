
# Similar IP Identification report


**Purpose: 
To capture the possibility of academic misconduct in a Moodle based online quiz/test.**

**Description:**
*The report lists students who used the same IP to access modules in Moodle.
It Filters through options such as modules and dates. 
Moodle saves activities done by users as log stores in the database. This information includes activity done, IP address, Origin of IP, timestamp, and username. This report uses the same data to find similar IP address logged with different users in the same activity.*

**Workings:** 

The report filters through Moodle logs and fetches the fields which has same IP address used by different students for a particular module. Filters through the date and module for accurate results. 

**Installation :**

Step 1 

Download the Folder and unzip

Step 2 

Move the folder "examcheck" in *moodle/local* folder in the server

Step 3 

Login as moodle admin and update the plugin. The addition should show up as soon as you open the dashboard. After updating, Go to any course->settings, It should display a plugin named as "examcheck". 

Change version number in version.php if neccessary.


**MIT License**

Copyright (c) 2021 Krishna Vyas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


