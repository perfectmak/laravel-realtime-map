# Laravel Realtime Map

This application implements a [Pusher](https://pusher.com) server that broadcasts location updates when it receives a web request. The code for the frontend map that responds to the location update can be found [here](https://github.com/perfectmak/angular-realtime-map). There is also an tutorial explaining how this work in detail and can be found [here](https://pusher.com/tutorials/realtime-map-laravel/).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
You would need to have PHP installed on your local machine to have this project running.
See [here](http://php.net/manual/en/install.php) for instruction on how to install PHP on your particular operating system.

### Setup Instructions
1. Clone this repository and `cd` into it.
2. Configure your environment variables for Pusher and Laravel by copying the `.env.example` to `.env`
5. Install composer dependencies
4. Run the Server using `php artisan serve`

### Testing the Application
See [here](https://github.com/perfectmak/angular-realtime-map#3-test-the-application) for how to test this application.


## Built With
* [Laravel](https://laravel.com/) - PHP Framework for Web Artisans
* [Pusher](https://pusher.com/) - APIs to enable devs building realtime features
