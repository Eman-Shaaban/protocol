
#Request Skeleton Definition
`{
  tag: 1, //integer, optional
    traceId: "tag", //optional, for debugging purposes
    cmd: "string", //required (get, subscribe, delete, update, read, count)
    cmdOpts: {}, //optional, options for the command (enable/disable things for example)
    r: '/_system/tools', //R is the resource you are talking to
    rev: 42, // integer, the revision of this R
    body: {} //optional
}`
