FROM quay.io/openshiftlabs/apb-base:1.2

LABEL "com.redhat.apb.spec"=\
"dmVyc2lvbjogMS4wCm5hbWU6IGRldm9wcy13b3Jrc2hvcC1hcGIKZGVzY3JpcHRpb246IEFQQiB0\
byBkZXBsb3kgcmVxdWlyZWQgaW5mcmEgY29tcG9uZW50cyBmb3IgdGhlIERldk9wcyBXb3Jrc2hv\
cCBvbiBhbiBPcGVuU2hpZnQgY2x1c3RlcgpiaW5kYWJsZTogRmFsc2UKYXN5bmM6IG9wdGlvbmFs\
CnRhZ3M6Ci0gd29ya3Nob3AKbWV0YWRhdGE6CiAgZGVwZW5kZW5jaWVzOiBbXQogIGRpc3BsYXlO\
YW1lOiAiRGV2T3BzIFdvcmtzaG9wIEluc3RhbGxlciIKICBsb25nRGVzY3JpcHRpb246ICJJbnN0\
YWxscyB0aGUgbGFiIGluc3RydWN0aW9ucyBhbmQgcmVxdWlyZWQgY29tcG9uZW50cyAoR2l0IHNl\
cnZlciwgZXRjKSBmb3IgcnVubmluZyB0aGUgRGV2T3BzIFdvcmtzaG9wIGh0dHBzOi8vZ2l0aHVi\
LmNvbS9vcGVuc2hpZnQtbGFicy9kZXZvcHMtZ3VpZGVzIgogIGNvbnNvbGUub3BlbnNoaWZ0Lmlv\
L2ljb25DbGFzczogInBmaWNvbiBwZmljb24tcHJvY2Vzcy1hdXRvbWF0aW9uIgogIHByb3ZpZGVy\
RGlzcGxheU5hbWU6ICJSZWQgSGF0LCBJbmMuIgpwbGFuczoKICAtIG5hbWU6IGRlZmF1bHQKICAg\
IGRlc2NyaXB0aW9uOiBEZXBsb3lzIERldk9wcyBXb3Jrc2hvcCBJbmZyYXN0cnVjdHVyZQogICAg\
ZnJlZTogVHJ1ZQogICAgbWV0YWRhdGE6CiAgICAgIGRpc3BsYXlOYW1lOiBEZWZhdWx0CiAgICBw\
YXJhbWV0ZXJzOgogICAgLSBuYW1lOiBvcGVuc2hpZnRfYWRtaW5fdXNlcgogICAgICB0aXRsZTog\
VXNlcm5hbWUKICAgICAgZGVzY3JpcHRpb246IEFkbWluIHVzZXIgaXMgcmVxdWlyZWQgZm9yIGNy\
ZWF0aW5nIGNsdXN0ZXIgcmVzb3VyY2VzCiAgICAgIHR5cGU6IHN0cmluZwogICAgICByZXF1aXJl\
ZDogdHJ1ZQogICAgICBkaXNwbGF5X2dyb3VwOiBPcGVuU2hpZnQgQWRtaW4gVXNlcgogICAgLSBu\
YW1lOiBvcGVuc2hpZnRfYWRtaW5fcGFzc3dvcmQKICAgICAgdGl0bGU6IFBhc3N3b3JkCiAgICAg\
IGRlc2NyaXB0aW9uOiBBZG1pbiBwYXNzd29yZCBpcyByZXF1aXJlZCBmb3IgY3JlYXRpbmcgY2x1\
c3RlciByZXNvdXJjZXMKICAgICAgdHlwZTogc3RyaW5nCiAgICAgIHJlcXVpcmVkOiB0cnVlCiAg\
ICAgIGRpc3BsYXlfdHlwZTogcGFzc3dvcmQKICAgICAgZGlzcGxheV9ncm91cDogT3BlblNoaWZ0\
IEFkbWluIFVzZXIKICAgIC0gbmFtZTogb3BlbnNoaWZ0X21hc3Rlcl91cmwKICAgICAgdGl0bGU6\
IE9wZW5TaGlmdCBNYXN0ZXIgVVJMCiAgICAgIGRlc2NyaXB0aW9uOiBUaGUgYWRkcmVzcyB0byBP\
cGVuU2hpZnQgbWFzdGVyIFVSTCB0byBiZSBkaXNwbGF5ZWQgaW4gdGhlIGxhYiBndWlkZSB0byBw\
YXJ0aWNpcGFudHMKICAgICAgdHlwZTogc3RyaW5nCiAgICAgIHJlcXVpcmVkOiB0cnVlCiAgICAg\
IGRpc3BsYXlfdHlwZTogc3RyaW5nCiAgICAgIGRpc3BsYXlfZ3JvdXA6IExhYiBHdWlkZQogICAg\
LSBuYW1lOiBpbmZyYXN2Y3NfYWRtX3VzZXIKICAgICAgdGl0bGU6IEluZnJhIFNlcnZpY2VzIEFk\
bWluIFVzZXIKICAgICAgZGVzY3JpcHRpb246IEFkbWluIHVzZXIgZm9yIGluZnJhc3RydWN0dXJl\
IHNlcnZpY2VzIChHb2dzLCBDaGUsIC4uLikKICAgICAgdHlwZTogc3RyaW5nCiAgICAgIGRlZmF1\
bHQ6ICJhZG1pbnVzZXIiCiAgICAgIHJlcXVpcmVkOiB0cnVlCiAgICAgIGRpc3BsYXlfdHlwZTog\
dGV4dAogICAgICBkaXNwbGF5X2dyb3VwOiBXb3Jrc2hvcCBJbmZyYSBTZXJ2aWNlcwogICAgLSBu\
YW1lOiBpbmZyYXN2Y3NfYWRtX3B3ZAogICAgICB0aXRsZTogSW5mcmEgU2VydmljZXMgQWRtaW4g\
UGFzc3dvcmQKICAgICAgZGVzY3JpcHRpb246IEFkbWluIHBhc3N3b3JkIGZvciBpbmZyYXN0cnVj\
dHVyZSBzZXJ2aWNlcyAoR29ncywgQ2hlLCAuLi4pCiAgICAgIHR5cGU6IHN0cmluZwogICAgICBk\
ZWZhdWx0OiAiYWRtaW5wd2QiCiAgICAgIHJlcXVpcmVkOiB0cnVlCiAgICAgIGRpc3BsYXlfdHlw\
ZTogdGV4dAogICAgICBkaXNwbGF5X2dyb3VwOiBXb3Jrc2hvcCBJbmZyYSBTZXJ2aWNlcwogICAg\
LSBuYW1lOiBnb2dzX2dlbl91c2VyX2NvdW50CiAgICAgIHRpdGxlOiBOdW1iZXIgb2YgVXNlcnMK\
ICAgICAgZGVzY3JpcHRpb246IE51bWJlciBvZiBHb2dzIHVzZXIgdG8gYmUgY3JlYXRlZAogICAg\
ICB0eXBlOiBpbnQKICAgICAgZGVmYXVsdDogMTAwCiAgICAgIHJlcXVpcmVkOiB0cnVlCiAgICAg\
IGRpc3BsYXlfZ3JvdXA6IEdpdCBTZXJ2ZXIKICAgIC0gbmFtZTogZ29nc19nZW5fdXNlcl9wd2QK\
ICAgICAgdGl0bGU6IFVzZXIgUGFzc3dvcmQKICAgICAgZGVzY3JpcHRpb246IFBhc3N3b3JkIGZv\
ciBHb2dzIHVzZXJzCiAgICAgIHR5cGU6IHN0cmluZwogICAgICBkZWZhdWx0OiAib3BlbnNoaWZ0\
IgogICAgICByZXF1aXJlZDogdHJ1ZQogICAgICBkaXNwbGF5X2dyb3VwOiBHaXQgU2VydmVyCiAg\
ICAgIA=="







COPY playbooks /opt/apb/actions
ADD requirements.yml /opt/apb/actions/requirements.yml
RUN ansible-galaxy install -r /opt/apb/actions/requirements.yml -f
RUN chmod -R g=u /opt/{ansible,apb}
USER apb
