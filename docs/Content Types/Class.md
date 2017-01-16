# Class
Class content type is used for adding Classes on the site.

### Fields
| Name  | Machine name | Required | Description |
| ------------- | ------------- | ------------- | ------------- |
| Title  | drupal's default  | Yes | Title of the class item. |
| Program Subcategory  | field\_class_activity  | No | A reference field for selecting the class. |
| **Content Area** | Field group|||
| Description | field\_class_description | No | Textarea for the description/body with WYSIWYG, without summary. |
| Content | field_content | No | A paragraph embed field that will allow us to add various flexible content modules, from the predefined list of paragraph types. |
| **Sidebar Area** | Field group |||
| Content | field\_sidebar_content | No | A paragraph embed field that will allow us to add various flexible content modules, from the predefined list of paragraph types. |

### URL pattern
Content type is using following pattern:
`/programs/[node:field_category_program:title]/[node:field_activity_category:title]/[node:field_class_activity:title]/[node:title]`