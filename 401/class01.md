# Node Ecosystem, TDD, CI/CD

1. Array.map() creates a new array populating with results of calling a specific function on every element.

2. Array.reduce() executes a reducer function that results in a single output.

3. superagent()
> request
   .post('/api/pet')
   .send({ name: 'Manny', species: 'cat' })
   .set('X-API-Key', 'foobar')
   .set('Accept', 'application/json')
   .then(res => {
      alert('yay got ' + JSON.stringify(res.body));
   });


> auth = await loginUser(user, request);
request.get(testUrl)
    .set('Authorization', `bearer ${auth.token}`)
    .expect(200, done);


4. Promises happen when a function needs time to execute, the compiler promises the function to get back to it and run it when it needs time.

5. Are all callback functions considered to be Asynchronous? No. Simply taking a callback doesn't make a function asynchronous. There are many examples of functions that take a function argument but are not asynchronous. For example there's forEach in Array. It iterates over each item and calls the function once per item.