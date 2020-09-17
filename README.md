# react-Native
gernal references about component


how to View base 64 image

const encodedBase64 = 'R0lGODlhAQABAIAAAAAA...7';
<Image source={{uri: `data:image/gif;base64,${encodedBase64}`}} />






// export const requestPostApi = async (endPoint, body, method) => {
//   console.log('testing hello', endPoint, body, method);
//   var header = {};
//   header = {'Content-type': 'application/json', 'Cache-Control': 'no-cache'};

//   var url = baseUrl + endPoint;

//   // console.log('Request Url:-' + url + '\n')
//   // console.log(body + '\n')
//   // console.log(header + '\n')

//   try {
//     let response = await fetch(url, {
//       method: method,
//       body: JSON.stringify(body),
//       headers: header,
//     });
//     let data = await response.json();
//     console.log('datatata', data);
//     let code = await response.status;
//     console.log(code);

//     if (code == 200) {
//       let responseJson = await response.json();
//       console.log(responseJson);
//       return {responseJson: responseJson, err: null};
//     } else if (code == 400) {
//       let responseJson = await response.json();

//       //Completion block
//       return {responseJson: null, err: responseJson.message};
//     } else {
//       return {responseJson: null, err: 'Something went wrong!'};
//     }
//   } catch (error) {
//     return {
//       responseJson: null,
//       err: 'Something Went Wrong! Please check your internet connection.',
//     };
//     console.error(error);
//   }
// };
