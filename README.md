# rhcos-aliyun-pruner

Run the script with `./main.py 4.10`

Should work with OCP 4.10 + 4.11

## TODO

- [ ] Probably make a base class to derive Aliyun clients from
- [ ] Fetch builds.json
- [ ] Parse each meta.json and look for Aliyun uploads
- [ ] Build list of builds/Aliyun uploads that aren't tagged
- [ ] Create function to do deletion of untagged images
- [ ] Implement dry-run functionality
