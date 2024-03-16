---
database-plugin: basic
sticker: 1f9d1-200d-1f393
---

```yaml:dbfolder
name: student_database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 2
    isHidden: false
    sortIndex: 2
    width: 79
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      footer_formula: 
  Subjects:
    input: tags
    accessorKey: Subjects
    key: Subjects
    id: Subjects
    label: Subjects
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 154
    isSorted: false
    isSortedDesc: false
    options:
      - { label: "SACE 12METH", value: "SACE 12METH", color: "hsl(35,93%,88%)"}
      - { label: "SACE 12SPEC", value: "SACE 12SPEC", color: "hsl(35,93%,88%)"}
      - { label: "SACE 12PHYS", value: "SACE 12PHYS", color: "hsl(0,93%,88%)"}
      - { label: "SACE 12BIO", value: "SACE 12BIO", color: "hsl(121,93%,88%)"}
      - { label: "SACE 12CHEM", value: "SACE 12CHEM", color: "hsl(212,93%,88%)"}
      - { label: "PreSACE Science", value: "PreSACE Science", color: "hsl(212,93%,88%)"}
      - { label: "PreSACE Maths", value: "PreSACE Maths", color: "hsl(35,93%,88%)"}
      - { label: "UCAT", value: "UCAT", color: "hsl(279,93%,88%)"}
      - { label: "PreSACE English", value: "PreSACE English", color: "hsl(64,93%,88%)"}
      - { label: "SACE 11PHYS", value: "SACE 11PHYS", color: "hsl(0,93%,88%)"}
      - { label: "SACE 11CHEM", value: "SACE 11CHEM", color: "hsl(217,93%,88%)"}
      - { label: "SACE 11METH", value: "SACE 11METH", color: "hsl(32,93%,88%)"}
      - { label: "IB HL MATH AA", value: "IB HL MATH AA", color: "hsl(32,93%,88%)"}
      - { label: "IB HL MATH AI", value: "IB HL MATH AI", color: "hsl(38,93%,88%)"}
      - { label: "SACE English", value: "SACE English", color: "hsl(64,93%,88%)"}
      - { label: "IB HL CHEM", value: "IB HL CHEM", color: "hsl(209,93%,88%)"}
      - { label: "SACE English Lit", value: "SACE English Lit", color: "hsl(80, 95%, 90%)"}
      - { label: "12IB CHEM HL", value: "12IB CHEM HL", color: "hsl(341, 95%, 90%)"}
      - { label: "12IB BIO", value: "12IB BIO", color: "hsl(322, 95%, 90%)"}
      - { label: "SACE 11SPEC", value: "SACE 11SPEC", color: "hsl(38,93%,88%)"}
      - { label: "IB PHYS", value: "IB PHYS", color: "hsl(6, 95%, 90%)"}
      - { label: "SACE 11BIO", value: "SACE 11BIO", color: "hsl(9, 95%, 90%)"}
      - { label: "Med Interview Course", value: "Med Interview Course", color: "hsl(53, 95%, 90%)"}
      - { label: "IB ECO", value: "IB ECO", color: "hsl(183, 95%, 90%)"}
      - { label: "8553", value: "8553", color: "hsl(146, 95%, 90%)"}
      - { label: "8709", value: "8709", color: "hsl(202, 95%, 90%)"}
      - { label: "11BIO", value: "11BIO", color: "hsl(4, 95%, 90%)"}
      - { label: "IB BIO", value: "IB BIO", color: "hsl(107, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      footer_formula: 
      option_source: manual
  Student_year_level:
    input: tags
    accessorKey: Student_year_level
    key: Student_year_level
    id: Student_year_level
    label: Student year level
    position: 12
    skipPersist: false
    isHidden: false
    sortIndex: 2
    isSorted: true
    isSortedDesc: true
    options:
      - { label: "Year 7", value: "Year 7", color: "hsl(194, 95%, 90%)"}
      - { label: "Year 12", value: "Year 12", color: "hsl(224, 95%, 90%)"}
      - { label: "Year 11", value: "Year 11", color: "hsl(148, 95%, 90%)"}
      - { label: "Year 4", value: "Year 4", color: "hsl(284, 95%, 90%)"}
      - { label: "Year 6", value: "Year 6", color: "hsl(23, 95%, 90%)"}
      - { label: "Year 8", value: "Year 8", color: "hsl(149, 95%, 90%)"}
      - { label: "Year 10", value: "Year 10", color: "hsl(358, 95%, 90%)"}
      - { label: "Year 9", value: "Year 9", color: "hsl(150, 95%, 90%)"}
      - { label: "Completed year 12", value: "Completed year 12", color: "hsl(326, 95%, 90%)"}
      - { label: "[,Completed year 12]", value: "[,Completed year 12]", color: "hsl(345, 95%, 90%)"}
      - { label: "[,Year 10]", value: "[,Year 10]", color: "hsl(298, 95%, 90%)"}
      - { label: "[,Year 11]", value: "[,Year 11]", color: "hsl(293, 95%, 90%)"}
      - { label: "[,Year 12]", value: "[,Year 12]", color: "hsl(148, 95%, 90%)"}
      - { label: "[,Year 6]", value: "[,Year 6]", color: "hsl(160, 95%, 90%)"}
      - { label: "[,Year 7]", value: "[,Year 7]", color: "hsl(330, 95%, 90%)"}
      - { label: "[,Year 8]", value: "[,Year 8]", color: "hsl(133, 95%, 90%)"}
      - { label: "[,Year 9]", value: "[,Year 9]", color: "hsl(292, 95%, 90%)"}
      - { label: "Year 1", value: "Year 1", color: "hsl(331, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Student_email:
    input: text
    accessorKey: Student_email
    key: Student_email
    id: Student_email
    label: Student email
    position: 13
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 208
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Parent_email:
    input: text
    accessorKey: Parent_email
    key: Parent_email
    id: Parent_email
    label: Parent email
    position: 16
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 274
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      related_note_path: Templates/Untitled database.md
      asociated_relation_id: 
  Monday:
    input: select
    accessorKey: Monday
    key: Monday
    id: Monday
    label: Mon
    position: 18
    width: 57
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(67,93%,88%)"}
      - { label: "Currently available", value: "Currently available", color: "hsl(129,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Tuesday:
    input: select
    accessorKey: Tuesday
    key: Tuesday
    id: Tuesday
    label: Tue
    position: 19
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 77
    isSorted: false
    isSortedDesc: false
    options:
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(64,93%,88%)"}
      - { label: "Currently available", value: "Currently available", color: "hsl(141,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  School:
    input: text
    accessorKey: School
    key: School
    id: Subsidy
    label: School
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 177
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Student_mobile:
    input: text
    accessorKey: Student_mobile
    key: Student_mobile
    id: Student_phone
    label: Student mobile
    position: 14
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 128
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Parent_mobile:
    input: text
    accessorKey: Parent_mobile
    key: Parent_mobile
    id: Parent_phone
    label: Parent mobile
    position: 17
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 129
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Wednesday:
    input: select
    accessorKey: Wednesday
    key: Wednesday
    id: Wed
    label: Wed
    position: 20
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 49
    options:
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(61,93%,88%)"}
      - { label: "Currently available", value: "Currently available", color: "hsl(126,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Thursday:
    input: select
    accessorKey: Thursday
    key: Thursday
    id: Thu
    label: Thu
    position: 21
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Currently available", value: "Currently available", color: "hsl(121,93%,88%)"}
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(61,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Friday:
    input: select
    accessorKey: Friday
    key: Friday
    id: Fri
    label: Fri
    position: 22
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Currently available", value: "Currently available", color: "hsl(114,93%,88%)"}
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(73,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Saturday_AM:
    input: select
    accessorKey: Saturday_AM
    key: Saturday_AM
    id: SatAM
    label: SatAM
    position: 23
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Currently available", value: "Currently available", color: "hsl(123,93%,88%)"}
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(64,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Saturday_PM:
    input: select
    accessorKey: Saturday_PM
    key: Saturday_PM
    id: SatPM
    label: SatPM
    position: 24
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Currently available", value: "Currently available", color: "hsl(114,93%,88%)"}
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(61,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Sunday_AM:
    input: select
    accessorKey: Sunday_AM
    key: Sunday_AM
    id: SunAM
    label: Sun AM
    position: 25
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Currently available", value: "Currently available", color: "hsl(114,93%,88%)"}
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(58,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Sunday_PM:
    input: select
    accessorKey: Sunday_PM
    key: Sunday_PM
    id: SunPM
    label: SunPM
    position: 26
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 77
    options:
      - { label: "Currently available", value: "Currently available", color: "hsl(119,93%,88%)"}
      - { label: "I can make myself available", value: "I can make myself available", color: "hsl(61,93%,88%)"}
      - { label: "Definitely unavailable", value: "Definitely unavailable", color: "hsl(0,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Current:
    input: select
    accessorKey: Current
    key: Current
    id: current?
    label: Current
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    isSorted: false
    isSortedDesc: false
    options:
      - { label: "Current", value: "Current", color: "hsl(104,93%,88%)"}
      - { label: "Potential", value: "Potential", color: "hsl(44,93%,88%)"}
      - { label: "Past", value: "Past", color: "hsl(0,93%,88%)"}
      - { label: "Ex-staff", value: "Ex-staff", color: "hsl(298, 95%, 90%)"}
      - { label: "Potential employee", value: "Potential employee", color: "hsl(287, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      footer_formula: 
  Classes:
    input: relation
    accessorKey: Classes
    key: Classes
    id: newColumn19
    label: Classes
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 164
    isSorted: false
    isSortedDesc: true
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      asociated_relation_id: 
      rollup_action: 
      related_note_path: 1.2 Classes/Classes database.md
      relation_color: hsl(0,8%,30%)
      footer_formula: 
  Day:
    input: rollup
    accessorKey: Day
    key: Day
    id: newColumn20
    label: Day
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 295
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      asociated_relation_id: Classes
      rollup_action: Original Value
      rollup_key: Day
      persist_rollup: true
      content_vertical_alignment: align-middle
      content_alignment: text-align-center
      wrap_content: true
  ClassTime:
    input: rollup
    accessorKey: ClassTime
    key: ClassTime
    id: newColumn21
    label: Time
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 43
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      asociated_relation_id: Classes
      rollup_action: Original Value
      rollup_key: Time
      wrap_content: true
      persist_rollup: true
  Parent_name:
    input: text
    accessorKey: Parent_name
    key: Parent_name
    id: newColumn11
    label: Parent name
    position: 15
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 167
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Subsidy:
    input: text
    accessorKey: Subsidy
    key: Subsidy
    id: Subsidy
    label: Subsidy
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 130
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  SACE_or_IB:
    input: select
    accessorKey: SACE_or_IB
    key: SACE_or_IB
    id: newColumn23
    label: SACE / IB
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "SACE", value: "SACE", color: "hsl(52, 95%, 90%)"}
      - { label: "IB", value: "IB", color: "hsl(127, 95%, 90%)"}
      - { label: "PreSACE", value: "PreSACE", color: "hsl(256,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Student_name:
    input: text
    accessorKey: Student_name
    key: Student_name
    id: Student_name
    label: Student_name
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      footer_formula: 
config:
  remove_field_when_delete_column: true
  cell_size: normal
  sticky_first_column: true
  group_folder_column: 
  remove_empty_folders: true
  automatically_group_files: true
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: Templates/Student template.md
  pagination_size: 200
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: true
  implementation: default
  show_metadata_tags: false
filters:
  enabled: true
  conditions:
      - condition: AND
        disabled: true
        label: "Current"
        color: "hsl(107,93%,88%)"
        filters:
        - field: Current
          operator: CONTAINS
          value: "Current"
          type: text
      - condition: OR
        disabled: true
        label: "Potential"
        color: "hsl(38,93%,88%)"
        filters:
        - field: Current
          operator: CONTAINS
          value: "Potential"
          type: text
        - field: Current
          operator: EQUAL
          value: ""
          type: text
      - condition: AND
        disabled: true
        label: "Past"
        color: "hsl(0,93%,88%)"
        filters:
        - field: Current
          operator: CONTAINS
          value: "Past"
          type: text
```