verified# effective-fiesta
woodlum_music.com/Result.Successbc1qk2sg8gnkka6raad4yxkpxt2r2d0sd2n7yzu06k// show loading UI

// Request the session ID with Fuel or other network libraries

Fuel.post("https://{{YOUR_SERVER_BASE_URL}}/create-verification-session")

  .responseString { _, _, result ->

        when (result) {

                  is Result.Failure -> {

                                // show error UI

                                          }

                                                    is Result.Success -> {

                                                                  val responseJson = JSONObject(result.value)

                                                                                try {

                                                                                                  // start verification session

                                                                                                                    identityVerificationSheet.present(

                                                                                                                                          verificationSessionId =

                                                                                                                                                                  responseJson.getString("id"),

                                                                                                                                                                                        ephemeralKeySecret =

                                                                                                                                                                                                                responseJson.getString("ephemeral_key_secret")

                                                                                                                                                                                                                                  )

                                                                                                                                                                                                                                                } catch (t: Throwable) {

                                                                                                                                                                                                                                                                  // show error UI

                                                                                                                                                                                                                                                                                }

                                                                                                                                                                                                                                                                                          }

                                                                                                                                                                                                                                                                                                }

                                                                                                                                                                                                                                                                                                  }// show loading UI

                                                                                                                                                                                                                                                                                                  // Request the session ID with Fuel or other network libraries

                                                                                                                                                                                                                                                                                                  Fuel.post("https://{{YOUR_SERVER_BASE_URL}}/create-verification-session")

                                                                                                                                                                                                                                                                                                    .responseString { _, _, result ->

                                                                                                                                                                                                                                                                                                          when (result) {

                                                                                                                                                                                                                                                                                                                    is Result.Failure -> {

                                                                                                                                                                                                                                                                                                                                  // show error UI

                                                                                                                                                                                                                                                                                                                                            }

                                                                                                                                                                                                                                                                                                                                                      is Result.Success -> {

                                                                                                                                                                                                                                                                                                                                                                    val responseJson = JSONObject(result.value)

                                                                                                                                                                                                                                                                                                                                                                                  try {

                                                                                                                                                                                                                                                                                                                                                                                                    // start verification session

                                                                                                                                                                                                                                                                                                                                                                                                                      identityVerificationSheet.present(

                                                                                                                                                                                                                                                                                                                                                                                                                                            verificationSessionId =

                                                                                                                                                                                                                                                                                                                                                                                                                                                                    responseJson.getString("id"),

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          ephemeralKeySecret =

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  responseJson.getString("ephemeral_key_secret")

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    )

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  } catch (t: Throwable) {

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    // show error UI

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  }

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            }

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  }

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    }