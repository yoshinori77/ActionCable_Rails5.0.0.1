# README

## Useful Refs:

* [github - DHH(actioncable-examples)](https://github.com/rails/actioncable-examples)

* [github - Rails/ActionCable](https://github.com/rails/actioncable/tree/archive)

* [Action Cable Overview — Ruby on Rails Guides](http://edgeguides.rubyonrails.org/action_cable_overview.html)

* [Qiita - WebSocket と ActionCable(mizchi)](http://qiita.com/mizchi/items/44f181fb49f4c7f43771)

## Hint

config/cable.yml
case of redis
> production: &production
>   adapter: redis
>   url: redis://10.10.3.153:6381
> development: &development
>   adapter: redis
>   url: redis://localhost:6379
> test: *development


## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[Yoshinori Yamashita](https://github.com/yoshinori77/)
