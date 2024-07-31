# Spring-Notes

# how to use REST API
@RestController
@RequestMapping("/posts")
@GetMpping
@PostMpping @RequestBody
@PutMapping
@DeleteMapping @PathVariable("id")

@Component for utility class

# how to configure spring boot application

# Security
spring-boot-security
jwt
spring-security-jwt

Authorization @PreAuthorize("hasRole('USER')")

extends OncePerRequestFilter
http.addFilterBefore(jwtRequestFilter, UsernamePasswordAuthenticationFilter.class);

# Configuration
@Configuration
@EnableWebSecurity
for configuration class

# Thread.start()
for starting/run thread
thread.join() for deciding order pf threads to run
thread.sleep() pauses the thread
thread.interrupt()
thread.isAlive()

# @Transactional
class level or method level

@Autowire
@Qualifier(serverA) when you have multiple implpemetations on same interface
