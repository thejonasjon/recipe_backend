# recipi_backend

# Recipe Backend API

This is the backend API for Recipi, a platform for sharing and discovering recipes. The API is built using Django and Django Rest Framework, and can be easily set up using Docker.


## Getting Started

To get started with the Recipe Backend API, follow these steps:

1. Clone the repository:
git clone https://github.com/thejonasjon/recipi_backend.git

2. Build the Docker images:
docker build .

3. Navigate to the proxy folder and build the Docker image:
cd proxy
docker build .

4. Return to the main directory:
cd..

5. Run Docker Compose to build the development environment:
docker-compose -f docker-compose.yml up

6. You're all set! The development environment should now be up and running.


## Other Commands

- To run tests:
docker-compose run --rm app sh -c "python manage.py test"

- To run lint check:
docker-compose run --rm app sh -c "flake8"


## Contributing

Contributions are welcome! If you find any issues or would like to add new features, feel free to open an issue or submit a pull request.

## License

This project is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

In jurisdictions that recognize copyright laws, the author or authors of this software dedicate any and all copyright interest in the software to the public domain. We make this dedication for the benefit of the public at large and to the detriment of our heirs and successors. We intend this dedication to be an overt act of relinquishment in perpetuity of all present and future rights to this software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <https://unlicense.org>.



Feel free to copy and paste this into your README file!





