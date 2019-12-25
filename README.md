## Tracking Group members



    oc login <...>
    oc new-project gumbals
    oc new-app https://github.com/ekambaral/gumbals\
       -e CLOUDINARY_NAME=<your-cloudinary-name> \
       -e CLOUDINARY_KEY=<your-cloudinary-key> \ 
       -e CLOUDINARY_SECRET=<your-cloudinary-secret>
    oc logs -f bc/gumbals
    oc expose service gumbals
    oc get route
