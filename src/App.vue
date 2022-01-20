...
mounted () {
  axios
    .get('https://backend.demo.test/api/hello-there-nivel')
    .then(response => (this.msg = response.data))
}
...