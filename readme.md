# Laravel Realtime Map

This application implements a [Pusher](https://pusher.com) server that broadcasts location updates when it receives a web request.

The code for the frontend map that responds to the location update can be found [here](https://github.com/perfectmak/angular-realtime-map).


# Setup Instructions
1. Clone this repository and `cd` into it.
2. Configure your environment variables for Pusher and Laravel by copying the `.env.example` to `.env`
5. Install composer dependencies
4. Run the Server using `php artisan serve`