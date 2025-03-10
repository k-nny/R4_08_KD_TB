# Exercice 1

# Partie 1

# Question 1
docker build . ("." représentant le dossier ou se situe le fichier "Dockerfile")

# Question 2

PS P:\BUT2\S4A\Virtualisation\TD1\Ex1> docker build .
[+] Building 2.2s (5/5) FINISHED                                                                                                                                                      docker:desktop-linux
 => [internal] load build definition from Dockerfile                                                                                                                                                  0.0s
 => => transferring dockerfile: 48B                                                                                                                                                                   0.0s 
 => [internal] load metadata for docker.io/library/alpine:latest                                                                                                                                      1.6s 
 => [internal] load .dockerignore                                                                                                                                                                     0.0s
 => => transferring context: 2B                                                                                                                                                                       0.0s 
 => [1/1] FROM docker.io/library/alpine:latest@sha256:a8560b36e8b8210634f77d9f7f9efd7ffa463e380b75e2e74aff4511df3ef88c                                                                                0.5s 
 => => resolve docker.io/library/alpine:latest@sha256:a8560b36e8b8210634f77d9f7f9efd7ffa463e380b75e2e74aff4511df3ef88c                                                                                0.0s 
 => => sha256:f18232174bc91741fdf3da96d85011092101a032a93a388b79e99e69c2d5c870 3.64MB / 3.64MB                                                                                                        0.4s 
 => => sha256:a8560b36e8b8210634f77d9f7f9efd7ffa463e380b75e2e74aff4511df3ef88c 9.22kB / 9.22kB                                                                                                        0.0s 
 => => sha256:1c4eef651f65e2f7daee7ee785882ac164b02b78fb74503052a26dc061c90474 1.02kB / 1.02kB                                                                                                        0.0s 
 => => sha256:aded1e1a5b3705116fa0a92ba074a5e0b0031647d9c315983ccba2ee5428ec8b 581B / 581B                                                                                                            0.0s 
 => => extracting sha256:f18232174bc91741fdf3da96d85011092101a032a93a388b79e99e69c2d5c870                                                                                                             0.1s
 => exporting to image                                                                                                                                                                                0.0s 
 => => exporting layers                                                                                                                                                                               0.0s 
 => => writing image sha256:aded1e1a5b3705116fa0a92ba074a5e0b0031647d9c315983ccba2ee5428ec8b