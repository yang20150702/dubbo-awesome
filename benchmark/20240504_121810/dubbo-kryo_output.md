# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.857 ops/ms
Iteration   1: 7.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.267 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.246 ops/ms
Iteration   1: 11.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.928 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.422 ops/ms
Iteration   1: 13.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.240 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.819 ops/ms
Iteration   1: 9.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.202 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ±(99.9%) 0.069 ms/op
Iteration   1: 2.051 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.051 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ±(99.9%) 0.049 ms/op
Iteration   1: 1.714 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.714 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.308 ±(99.9%) 0.058 ms/op
Iteration   1: 1.960 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.960 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ±(99.9%) 0.120 ms/op
Iteration   1: 3.719 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.719 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ±(99.9%) 0.102 ms/op
Iteration   1: 2.142 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.509 ms/op
                 createUser·p0.50:   1.917 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.983 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  15.286 ms/op
                 createUser·p0.9999: 15.368 ms/op
                 createUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14915
  mean =      2.142 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 479 
    [ 1.250,  2.500) = 12420 
    [ 2.500,  3.750) = 1514 
    [ 3.750,  5.000) = 161 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.983 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     15.368 ms/op
     p(99.9990) =     15.368 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ±(99.9%) 0.073 ms/op
Iteration   1: 1.893 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.544 ms/op
                 existUser·p0.50:   1.790 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.531 ms/op
                 existUser·p0.99:   3.459 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16886
  mean =      1.893 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 804 
    [ 1.250,  2.500) = 15166 
    [ 2.500,  3.750) = 778 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      3.459 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.136 ±(99.9%) 0.079 ms/op
Iteration   1: 1.943 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.469 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.355 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  12.354 ms/op
                 getUser·p0.9999: 12.660 ms/op
                 getUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16457
  mean =      1.943 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 275 
    [ 1.250,  2.500) = 15047 
    [ 2.500,  3.750) = 871 
    [ 3.750,  5.000) = 177 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     12.660 ms/op
     p(99.9990) =     12.861 ms/op
     p(99.9999) =     12.861 ms/op
    p(100.0000) =     12.861 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.077 ±(99.9%) 0.162 ms/op
Iteration   1: 3.479 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.478 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.591 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 13.206 ms/op
                 listUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9179
  mean =      3.479 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 916 
    [ 2.500,  3.750) = 5317 
    [ 3.750,  5.000) = 2633 
    [ 5.000,  6.250) = 160 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.591 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.267          ops/ms
ClientSimple.existUser                       thrpt         11.928          ops/ms
ClientSimple.getUser                         thrpt         13.240          ops/ms
ClientSimple.listUser                        thrpt          9.202          ops/ms
ClientSimple.createUser                       avgt          2.051           ms/op
ClientSimple.existUser                        avgt          1.714           ms/op
ClientSimple.getUser                          avgt          1.960           ms/op
ClientSimple.listUser                         avgt          3.719           ms/op
ClientSimple.createUser                     sample  14915   2.142 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.509           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.917           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.983           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.365           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.286           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.368           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.368           ms/op
ClientSimple.existUser                      sample  16886   1.893 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.544           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.790           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.459           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.219           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.383           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.383           ms/op
ClientSimple.getUser                        sample  16457   1.943 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.469           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.276           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.354           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.660           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.861           ms/op
ClientSimple.listUser                       sample   9179   3.479 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.262           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.478           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.591           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.042           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.206           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.206           ms/op

Benchmark result is saved to 1714824817915.json
