## Steps

1. Initialize pnpm project (same with npm and yarn)
2. Add `supabase` as dev-dependency 
3. Login to supabase: `supabase login`
4. Initialize supabase project: `supabase init`
5. Link supabase project: `supabase link` 
6. Add an Edge Function named: `eqq`
7. Run `supabase start`

And the error is thrown:
```bash
Error: error during connect: this error may indicate that the docker daemon is not running: Get "http://%2F%2F.%2Fpipe%2Fdocker_engine/_ping": open //./pipe/docker_engine: The system cannot find the file specified.
  in github.com/supabase/cli/internal/utils.AssertDockerIsRunning:48
  in github.com/supabase/cli/internal/start.Run:35
```

I am using Windows 10. The error is thrown while using both cmd and git bash.
`supabase` command isn't available and I am using like `pnpm supabase ...`. Mentioned in case if it's relevant.
