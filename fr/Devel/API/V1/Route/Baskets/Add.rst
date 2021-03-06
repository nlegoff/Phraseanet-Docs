Ajouter un panier
=================

A propos
--------

Créé un nouveau panier

.. code-block:: bash

    /api/v1/baskets/add/

========================== =====
 Informations
========================== =====
 Méthode HTTP               GET
 Authentification requise   Oui
========================== =====

Paramètres
----------

======================== ============== =============
 Paramètres               Type           Information
======================== ============== =============
 name                     entier         Le nom du panier
======================== ============== =============

Attribut de la réponse
----------------------

============= ================================
 Attribut      Description
============= ================================
 basket        Le panier créé
============= ================================

Exemple de réponse
------------------

.. code-block:: javascript

    {
        "meta": {
            "api_version": "1.3",
            "request": "POST /api/v1/baskets/add/",
            "response_time": "2012-06-29T18:19:30+02:00",
            "http_code": 200,
            "error_type": null,
            "error_message": null,
            "error_details": null,
            "charset": "UTF-8"
        },
        "response": {
                "basket": {
                "basket_id": 148,
                "created_on": "2012-06-29T18:19:30+02:00",
                "description": "",
                "name": "test",
                "pusher_usr_id": null,
                "updated_on": "2012-06-29T18:19:30+02:00",
                "unread": false,
                "validation_basket": false
            }
        }
    }
