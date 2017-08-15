# Json Server - sample

Implementing a smple REST API end point using ``json-server`` is really simple.

First install the json-server using bellow command.

``npm install -g json-server``

This will install the ``json-server`` node module globally.

Now create a folder and create a ``.json`` file inside it. Say ``db.json``

Paste bellow content in the file.

``
{
    "contacts": [
        {
            "id": 1,
            "firstName": "John",
            "lastName": "Doe"
        },
        {
            "id": 2,
            "firstName": "Jane",
            "lastName": "Smith"
        },
        {
            "id": 3,
            "firstName": "Joe",
            "lastName": "Schmoe"
        },
        {
            "id": 4,
            "firstName": "Jill",
            "lastName": "Jones"
        },
        {
            "id": 5,
            "firstName": "Bill",
            "lastName": "Rogers"
        }
    ]
}
``

now open terminal and ``cd`` into the folder.

run ``json-server --watch db.json``

That's it. 

Your JSON Server will be running on port 3000.

Offecial Documentation
----------------------
https://github.com/typicode/json-server
