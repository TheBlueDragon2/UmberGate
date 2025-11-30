{
  "nodes": [
    {"id":"umbergate","type":"text","text":"**UMBERGATE**\nWesternmost town\nAnchorspan + Fracture","x":800,"y":300,"width":200,"height":140,"color":"1"},
    {"id":"fracture","type":"text","text":"THE FRACTURE\nMile-deep canyon","x":750,"y":100,"width":180,"height":300,"color":"6"},
    {"id":"wilds","type":"text","text":"**UMBERWILDS**\nFeral magic\nThe Maw","x":400,"y":200,"width":220,"height":180,"color":"3"},
    {"id":"cinder","type":"text","text":"Cinderfall\n3 days east","x":1100,"y":320,"width":160,"height":100},
    {"id":"lastford","type":"text","text":"Last Ford\n+7–8 days","x":1400,"y":300,"width":140,"height":100},
    {"id":"thorn","type":"text","text":"Thornmouth\n+4–5 days\nGreat port","x":1700,"y":280,"width":180,"height":110},
    {"id":"dominion","type":"text","text":"IRON DOMINION\nInvading west\nYear 6 of war","x":1900,"y":100,"width":220,"height":160,"color":"2"}
  ],
  "edges": [
    {"from":"umbergate","to":"cinder"},
    {"from":"cinder","to":"lastford"},
    {"from":"lastford","to":"thorn"},
    {"from":"umbergate","to":"fracture"},
    {"from":"fracture","to":"wilds"},
    {"from":"umbergate","to":"wilds","label":"Anchorspan"}
  ]
}