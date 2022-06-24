# Yevis workflow registry for DAT2-cwl

[![DOI](https://zenodo.org/badge/491358082.svg)](https://zenodo.org/badge/latestdoi/491358082)

This repository is a Yevis workflow registry that publishes [pitagora-network/DAT2-cwl](https://github.com/pitagora-network/DAT2-cwl) workflows using [Yevis-cli](https://github.com/sapporo-wes/yevis-cli).

You can browse the workflows at [https://pitagora-network.org/yevis-DAT2-cwl-browser/](https://pitagora-network.org/yevis-DAT2-cwl-browser/).
This web application is deployed to [pitagora-network/yevis-DAT2-cwl-browser](https://github.com/pitagora-network/yevis-DAT2-cwl-browser) using [Yevis-web](https://github.com/sapporo-wes/yevis-web).

If you want to get the workflows as a TRS API, execute as follows:

```bash=
$ curl -fsSL http://pitagora-network.org/yevis-DAT2-cwl/tools | jq .
[
  {
    "url": "https://pitagora-network.github.io/yevis-DAT2-cwl/tools/d03458d8-837c-4173-afa3-55ebe538b0b2",
    "id": "d03458d8-837c-4173-afa3-55ebe538b0b2",
    "organization": "@suecharo",
    "name": "DAT2-cwl - bacteria genome workflow",
    "tool_class": {
      "id": "workflow",
      "name": "Workflow",
      "description": "A computational workflow"
    },
    "description": "https://zenodo.org/api/files/af647e79-1ec9-4947-b7dd-c451faf4a511/README.md",
    "has_checker": true,
    "checker_url": "https://github.com/sapporo-wes/yevis-cli",
    "versions": [
      {
        "author": [
          "suecharo"
        ],
        "name": "DAT2-cwl - bacteria genome workflow",
        "url": "https://pitagora-network.github.io/yevis-DAT2-cwl/tools/d03458d8-837c-4173-afa3-55ebe538b0b2/versions/1.0.0",
        "id": "d03458d8-837c-4173-afa3-55ebe538b0b2",
        "descriptor_type": [
          "CWL"
        ],
        "verified": true,
        "verified_source": [
          "https://github.com/pitagora-network/yevis-DAT2-cwl/actions/runs/2317749577"
        ]
      }
    ]
  }
]
```
