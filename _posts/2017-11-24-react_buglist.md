---
title: React BugList
---

# {{ page.title }}

## 目录
+ [01 propTypes](#partI)
<!-- + [02](#partII) -->
<!-- + [03](#partIII) -->

----------------------------------

## 1.react组件中写入propTypes，控制台报错

报错：
'PropTypes' is not defined  no-undef
解决办法：
15.5.0版本之后，废除这个属性，所以需要单独引入prop-types这个包，
在组件中引入 import PropTypes from 'prop-types'
才可以在组件中使用：
ComponentChild.propTypes = {
    name: PropTypes.string
}

----------------------------------




{{ page.date|date_to_string }}