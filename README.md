Takeaway
=======================
[![Code Climate](https://codeclimate.com/github/TheoLeanse/takeaway-challenge/badges/gpa.svg)](https://codeclimate.com/github/TheoLeanse/takeaway-challenge)

![BOX_FOOD](http://www.smart-restaurants.co.uk/site/wp-content/uploads/2014/04/Chinese-Takeaway-Box-To-Take-Home.jpg)

## Technologies Used

- Ruby
- Rspec

## My favourite bit of the code:

~~~
  def price_of dish
    @menu[dish]
  end
~~~

## Favourite part of the tests:

~~~
 let(:order         ) { double :order, items: { :burger => 9.99 } }
 let(:notifier      ) { double :notifier, notify: nil }
 let(:message_centre) { double :message_centre, process: nil }
~~~

I enjoyed mocking and stubbing the Till class!

## Takeaways from Takeaway:

SOLID principles and BDD clicked for me with this project
