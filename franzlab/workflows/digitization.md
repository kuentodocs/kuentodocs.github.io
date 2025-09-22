---
layout: default
title: Digitization
parent: Franz Lab
has_children: true
nav_order: 2
---


# Digitization
{: .no_toc }

Digitization workflows for the weevil collection. Data publicly available on [GBIF](https://www.gbif.org/dataset/aae308f4-9f9c-4cdd-b4ef-c026f48be551). 
{: .fs-5 .fw-300 }

---

<div class="code-example" markdown="1">

<span class="fs-5">
New secimens should be **accessioned** before digitization.
</span>

</div>


## Before digitizing specimens

- Access the Specify [KUEntoPinned](https://entomology.specify.ku.edu) instance. Coordinate with collection managers to get access.

| [<img src="https://github.com/user-attachments/assets/f5c4854a-d069-4c12-bc3b-199d356c7df2" alt="Event Query"  width="480" height="500">](https://entomology.specify.ku.edu/) |

{: .highlight }
Select the specimen(s) to digitize and prepare the **catalog numbers** (barcodes). If specimens have been collected recently (e.g. current Franz Lab projects), make sure they are **accessioned** before digitizating. Coordinate with collection managers to get appropriate paperwork.

### Check data on the label(s)

{: .highlight }
**What do you see?**

- Country, state, county, locality?
- Coordinates, elevation?
- Date?
- Collector(s)?
- Habitat, collecting method?
- Field numbers?
- Determinations?

Every label is different. Don't worry if some elements are missing. 

| <img src="https://github.com/user-attachments/assets/af91134e-4bad-478c-933d-0105a92e7a9d" alt="Labels"  width="480" height="500"> |

### Collecting event number

To digitize specimens in Specify, you need a **_collecting event number_**, which will link all specimens collected in the same locality, in a particular date, by the same collector(s), with the same method. For example, all insects collected by N. Franz during the night of Aug 24, 2025 would share the same _collecting event number_. If more insects were collected that night by N. Franz on a particular plant, that sample would need a new _collecting event number_.

The **collecting event numbers** are generated in by the researchers OR are asigned by the person in charge of digitization, in the case of older specimens. _Collecting event numbers_ can vary in format, depending on the researcher. It usually contains country, state (in the case of the US), collector, year, and event number. 

| [<img src="https://github.com/user-attachments/assets/7b107c3a-1707-4361-b501-0cca97905eea" alt="CollEvUS"  width="480" height="500">](https://entomology.specify.ku.edu/specify/view/collectingevent/125414/) |

| [<img src="https://github.com/user-attachments/assets/340d8220-116d-4fa7-9bfd-2fb73d1e477b" alt="CollEvPanama"  width="480" height="500">](https://entomology.specify.ku.edu/specify/view/collectingevent/1994/) |

---

Before digitizing, you should obtain the correct _collecting event number_, by exploring existing collecting events (should match for locality, date, collector and method). In the case of new samples, codes have to be created following the preferred format. A list of 2025 collecting event numbers by N. Franz is available [here](https://kansas.sharepoint.com/:x:/t/FranzLab/ERPYc_iq79lCkkPA7ZNbF6gB6hQDf9rCABoX3qKdrw8KLQ?e=x7YMvO). The same list can be obtained running this [query](https://entomology.specify.ku.edu/specify/query/525/) in Specify. **Please don't modify or delete the query.** You can save your own copy using the _Save As_ option.

| [<img src="https://github.com/user-attachments/assets/ad6e0027-2606-4956-8b22-448c4e41c538" alt="Franz Events"  width="480" height="500">](https://entomology.specify.ku.edu/specify/query/521/) |

To search for collecting events, it helps adding the country, year, month, day, collector, locality, and coordinates. You can use this suggested query:

| [<img src="https://github.com/user-attachments/assets/976753cd-7fc5-4dbc-a3a0-b836ac9b91af" alt="Event Query"  width="480" height="500">](https://entomology.specify.ku.edu/specify/query/521/) |

If the _collecting event_ **is available**, just copy it and **you are ready to start digitizing**. If the _collecting event_ is not available, you need a **new code** to add a collecting _event_ in Specify. Please follow the appropriate format for Franz Lab's samples and for other specimens in the collection. Check with collection managers if you have questions about the format.

### New collecting events in Specify

1. To generate a new _Collecting Event_, you need to search the exact **locality** (including coordinates and elevation, if available). Use the following query to find the locality:
  
| [<img src="https://github.com/user-attachments/assets/4b3f9dd8-5c0a-4347-9dca-8379d4678a5c" alt="Locality Query"  width="480" height="500">](https://entomology.specify.ku.edu/specify/query/524/) |

- If the locality exists, **just copy the string to use it in Step 2**. If the locality doesn't exist, generate a new one ([Left Menu>Data entry>Locality](https://entomology.specify.ku.edu/specify/view/locality/new/)). The Geography values **must be selected from the available values** in the dropdown menu. For localities in the US, start typing the County to display the available values. For localities outside the US, start with State or Province. 

| [<img src="https://github.com/user-attachments/assets/1d69e8ae-caeb-43d5-a37c-355a2b9e09da" alt="Event Query"  width="480" height="500">](https://entomology.specify.ku.edu/specify/view/locality/new/) |

![LocalityTable](https://github.com/user-attachments/assets/a2283eb2-0a03-4205-a1e8-c36998e9388f)

| [<img src="https://github.com/user-attachments/assets/976753cd-7fc5-4dbc-a3a0-b836ac9b91af" alt="Event Query"  width="480" height="500">](https://entomology.specify.ku.edu/specify/query/521/) |

- Copy the locality string to use in the next step.

- Once you have copied the locality string, create a new _Collecting Information_ ([Left Menu>Data entry>Collecting Event](https://entomology.specify.ku.edu/specify/view/collectingevent/new/)).

| [<img src="https://github.com/user-attachments/assets/1fb3894e-da1c-4cd9-8c77-db308de59000" alt="Event Query"  width="480" height="500">](https://entomology.specify.ku.edu/specify/view/collectingevent/new/) |

![CollEventTable](https://github.com/user-attachments/assets/e1d4bb3e-4e7b-4282-803c-4aee44da768d)

-Copy the **_collecting event number_** to start digitizing your specimens.
  
## Digitizing specimens

{: .highlight }
Once you have the collecting event number, you can digitize the specimens (_collection objects_) associated with this event.

| <img src="https://github.com/user-attachments/assets/576cf7df-87ce-4d50-8257-4cda96e12582" alt="Labels"  width="400"> |

- Open a _New Collection Object_ form [(Left Menu>Data Entry>Collection Object)](https://entomology.specify.ku.edu/specify/view/collectionobject/new/).

| [<img src="https://github.com/user-attachments/assets/1348e408-2f58-49da-8711-485cbedb47c1" alt="New Collection Object"  width="480" height="500">](https://github.com/user-attachments/assets/574b8017-00ff-42c8-a936-44e88fa72a0c) |

![CollObjectTable](https://github.com/user-attachments/assets/cf7bdd55-e212-45eb-8ccf-623d1bae08f6)


Click to see example: 

| [<img src="https://github.com/user-attachments/assets/cbdfac37-d8a3-4cb8-8e47-6eae24d4a75d" alt="Collection Object"  width="480" height="500">](https://entomology.specify.ku.edu/specify/view/collectionobject/1481826/) |
