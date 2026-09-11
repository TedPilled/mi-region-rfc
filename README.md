# Michigan MeshCore Regions

This repository develops a shared region-scoping standard for Michigan MeshCore communities.

The draft treats regions as RF propagation and community domains, not political boundaries. Its purpose is to reduce unnecessary RF flooding while preserving useful connectivity at local, regional, statewide, and interstate scales.

## RFCs

- [RFC-001: Michigan MeshCore Regions](rfc/0001-michigan-regions.md) — Draft
- [RFC-001 Addendum A: Scoping Policy and Reference County Assignments](rfc/0001-addendum-a-scoping-and-county-reference.md) — Draft

## Current draft hierarchy

```text
us                           # United States
|
└── midwest                  # USA Midwest
    |
    ├── il                   # Illinois
    |
    ├── in                   # Indiana
    |
    └── mi                   # Michigan
    |   |
    │   ├── mi-c             # Central Michigan
    │   │   ├── mbs          # Midland / Bay City / Saginaw
    │   │   ├── jxn          # Jackson
    │   │   ├── fnt          # Flint
    │   │   ├── hls          # Hilldale
    │   │   ├── lns          # Lansing
    │   │   ├── mpl          # Mount Pleasant
    │   │   ├── tmb          # Thumb Area
    │   │   ├── tws          # Tawas
    │   │   └── wbr          # West Branch
    │   │
    |   ├── mi-w             # West Michigan
    │   │   ├── azo          # Kalamazoo
    │   │   ├── bcr          # Battle Creek
    │   │   ├── bnh          # Benton Harbor
    │   │   ├── grr          # Grand Rapids
    │   │   ├── hol          # Holland / Zeeland
    │   │   └── mkg          # Muskegon
    │   │
    │   ├── mi-e             # Eastern Michigan
    │   │   ├── adr          # Adrian
    │   │   ├── ann          # Ann Arbor 
    │   │   ├── bdf          # Bedford Township
    │   │   ├── blu          # Port Huron / Marysville
    │   │   ├── bri          # Brighton / Howell
    │   │   ├── det          # Metro Detroit
    │   │   └── lap          # Lapeer
    │   │
    │   ├── mi-n             # Northern Michigan
    │   │   ├── alp          # Alpena / Rogers City
    │   │   ├── bgr          # Big Rapids
    │   │   ├── cad          # Cadillac
    │   │   ├── gld          # Gaylord / Charlevoix / Petosky
    │   │   ├── gry          # Grayling / Kalkaska
    │   │   ├── hlk          # Houghton Lake
    │   │   ├── mac          # Mackinaw City / Cheboygan
    │   │   ├── man          # Manistee / Ludington / Frankfort
    │   │   ├── trv          # Traverse City
    │   │   └── mio          # Mio
    │   │
    │   └── mi-upper         # Upper Peninsula
    |       ├── mrq          # Marquette / Munising / Ishpeming
    |       ├── esc          # Escanaba / Gladstone
    |       ├── irm          # iron Mountain
    |       ├── irw          # ironwood
    |       ├── msq          # Manistique
    |       ├── nby          # Newberry
    |       ├── soo          # Sault St Marie
    |       ├── sti          # St Ignace
    |       └── kwn          # Ontanogan / Houghton / L'Anse
    │
    └── wi                   # Wisconsin
```

The city and neighboring-state examples illustrate how the model can scale; they do not establish hard boundaries or govern another community's regional structure.
