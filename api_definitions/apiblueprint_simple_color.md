# POST /webhook/v1/actions/solid_color

+ Request

        {"userId":"","actionFields":{"color":""}}

+ Response 401 (application/json;charset=utf-8)

    + Headers

            Access-Control-Allow-Origin: *
            Access-Control-Allow-Headers: content-type
            Transfer-Encoding: chunked

    + Body

            {"errors":[{"message":"invalid request"}]}


