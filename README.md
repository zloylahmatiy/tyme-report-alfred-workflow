# Tyme Report Alfred Workflow

## Version 0.1

Workflow for [Alfred](http://www.alfredapp.com/) to get report from [Tyme](http://tyme-app.com) app.

Workflow get time records from [Tyme](http://tyme-app.com) app and copy it to clipboard in CSV format.

Until now, this workflow is used primarily by me and it is therefore far from being without bugs etc.
Feel free to use it but use with caution.

## Installation

Just like every other workflow download the `Tyme Report.workflow` file and open it.

## Usage

`tyr` - keyword to run workflow

Arguments:

* `[dd[.mm[.yy[yy]]]]` - Start date. Yesterday by default.
* `[dd[.mm[.yy[yy]]]]` - End date. Yesterday by default.
* `[Project name]` - Project name. Use `all` - for all projects. All  projects by default.
* `[Task name]`	- Task name. Use `all` - for all tasks. All tasks by default.

## Examples

* `tyr` - Returns all time records for all projects and all tasks for yesterday.
* `tyr 11` - Returns all time records for all projects and all tasks for 11 day of current month and current year.
* `tyr 12 14` - Returns all time records for all projects and all tasks for period from 12 day of current month and current year to 14 day of current month and current year.
* `tyr 12.10` - Returns all time records for all projects and all tasks for 12 day of 10 month and current year.
* `tyr 12.10.2020 14.11.2020` - Returns all time records for all projects and all tasks for period from 12.10.2020 to 14.11.2020.
* `tyr 12.10.2020 14.11.2020 Project1` - Returns all time records for Project1 project and all tasks for period from 12.10.2020 to 14.11.2020.
* `tyr 12.10.2020 14.11.2020 Project1 Task1` - Returns all time records for Project1 project and Task1 task for period from 12.10.2020 to 14.11.2020.
* `tyr 12.10.2020 14.11.2020 all Task1` - Returns all time records for all projects and Task1 task for period from 12.10.2020 to 14.11.2020.

## Licence

This code is licensed under the [MIT Licence](https://opensource.org/licenses/MIT).

The icon belongs to and is used here with the permission of [Tyme](http://tyme-app.com).