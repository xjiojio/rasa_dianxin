## New Story 1

- greet
  - utter_greet
- request_search{"time": "上个月", "item": "消费"}
  - slot{"item": "消费"}
  - slot{"time": "上个月"}
  - action_search_consume
- request_search{"item": "消费"}
  - slot{"item": "消费"}
  - action_search_consume
- inform_time{"time": "四月"}
  - slot{"time": "四月"}
  - action_search_consume

- request_search{"time":"四月","item":"消费"}
  - slot{"item":"消费"}
  - slot{"time":"四月"}
  - action_search_consume

- goodbye
  - utter_goodbye

* greet
    - utter_greet
* greet
    - utter_greet
