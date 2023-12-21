# build-immortalwrt-mt798x
Build ImmortalWrt-mt798x with GitHub Actions

## How to use
1. fork this repo
2. run workflow under `Actions` tab
3. wait until the ssh info shows up
4. copy the default config file
5. run `make menuconfig`
6. exit the ssh session
7. wait until it is finished

## Warning
Please be careful that the SSH login information will be shown publicly if your repository is public.

If you have registered a public SSH key with your GitHub profile, you can change [line 52](https://github.com/tar-xz/build-immortalwrt-mt798x/blob/cd1e48f085467d7d2d9f7e488d7f59dd15cbdd7e/.github/workflows/main.yml#L52) to true in order to log in with your private key.

---

### Enjoy
