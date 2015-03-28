- Answer these CodeLearn Rails Models exercise questions:
  - What model method allows you to make a new model instance and save it?

The create method

  - If I wanted to find all `Bulldog`s with the `breed` of `'English'`, what line in Ruby would I execute?

Bulldog.where("breed = 'English'") or Bulldog.where(breed: 'English')

  - How do you delete all instance of a certain model?

Bulldog.destroy_all("breed = 'English'") or Bulldog.destroy_all(breed: 'English')

- RailsTutorial Ch. 6
  - Link to `sample_app` repo: [my repo](http://is.here)
  - Link to app on Heroku: [my app](http://is.here)
