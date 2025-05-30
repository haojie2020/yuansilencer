---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      user_groups:
        - Principal Investigator
        - Researchers
        - Student Assistant
        - Technician
        - Visitors
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: people
    content:
      title: Alumni
      user_groups:
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true      # 可以改为 false 如果不显示以前的头衔
      show_organization: true   # 需要主题支持
      show_social: false
---
