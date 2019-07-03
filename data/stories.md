## Generated Story 2862175621717897367
* greet
    - utter_greet
* request_search{"time": "上个月", "item": "消费"}
    - slot{"item": "消费"}
    - slot{"time": "上个月"}
* request_search{"item": "消费"}
    - slot{"item": "消费"}
    - utter_ask_time
* inform_time{"time": "四月"}
    - slot{"time": "四月"}
    - ActionSearchConsume
* request_search{"item": "消费"}
    - slot{"item": "消费"}
    - rewind
* request_search{"item": "消费"}
    - slot{"item": "消费"}
    - utter_ask_time
* inform_time{"time": "四月"}
    - slot{"time": "四月"}
    - ActionSearchConsume
* goodbye
