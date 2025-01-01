# Countries Provinces and Cities

This project provides data for provinces/states and cities of various countries. Currently, the following countries are included:

- **Iran**: Detailed list of provinces and cities.
- **Germany**: Comprehensive list of federal states (Bundesländer) and their cities.

If you use languages other than JavaScript and need these lists, you can access the JSON and MySQL Information through this [repository](https://github.com/mohammad-prb/provinces-and-cities) on Github.

## Install
    npm i provinces-and-cities

## How to Use
    import { Iran } from 'provinces-and-cities'
    
    Iran.main    // all provinces and main cities
    Iran.all     // all provinces and all cities

### Examlpe of data
    Iran.main[7] = {
        "id": 8,
        "name": "تهران",
        "tel_prefix": "021",
        "cities": [
            "اسلامشهر",
            "بومهن",
            "پاكدشت",
            "تهران",
            "چهاردانگه",
            "دماوند",
            "رودهن",
            "ري",
            "شريف آباد",
            "شهر رباط كريم",
            "شهر شهريار",
            "فشم",
            "فيروزكوه",
            "قدس",
            "كهريزك",
            "لواسان بزرگ",
            "ملارد",
            "ورامين"
        ]
    }

## Future Plans
The project is designed to be scalable, and we plan to add data for other countries in the future. If you have suggestions for specific countries, feel free to contribute or create an issue.

## Contributions
We welcome contributions to expand this project. If you'd like to add data for a new country or improve existing data, please create a pull request.

## Support
If this project was helpful, please consider giving it a **star**. Your support helps us grow!
