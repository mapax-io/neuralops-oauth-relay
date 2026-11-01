# NeuralOps OAuth relay

One static page at `https://auth.neuralopsnexus.ai/oauth/relay`, the single redirect URI
every "Connect with NeuralOps" vendor app (GitHub, Atlassian, Google) is registered with.
It reads the install's address from the OAuth state and sends the browser home.
It stores nothing, calls nothing and holds no secret. The address must never change.
