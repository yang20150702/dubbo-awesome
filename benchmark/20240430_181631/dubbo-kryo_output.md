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
# Warmup Iteration   1: 1.598 ops/ms
Iteration   1: 6.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.285 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.954 ops/ms
Iteration   1: 12.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.237 ops/ms


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
# Warmup Iteration   1: 6.039 ops/ms
Iteration   1: 12.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.405 ops/ms


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
# Warmup Iteration   1: 5.106 ops/ms
Iteration   1: 9.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.348 ops/ms


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.084 ms/op
Iteration   1: 2.369 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.369 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.667 ±(99.9%) 0.059 ms/op
Iteration   1: 2.097 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.097 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ±(99.9%) 0.050 ms/op
Iteration   1: 1.787 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.787 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ±(99.9%) 0.110 ms/op
Iteration   1: 3.288 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.288 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.082 ms/op
Iteration   1: 2.359 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.503 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.798 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   4.770 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 18.945 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13570
  mean =      2.359 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 199 
    [ 1.250,  2.500) = 9833 
    [ 2.500,  3.750) = 3311 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      4.770 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     18.945 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.102 ±(99.9%) 0.069 ms/op
Iteration   1: 2.072 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.974 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  22.174 ms/op
                 existUser·p0.9999: 23.239 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15435
  mean =      2.072 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14245 
    [ 2.500,  5.000) = 1062 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =     22.174 ms/op
     p(99.9900) =     23.239 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 3.436 ±(99.9%) 0.083 ms/op
Iteration   1: 1.991 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   1.913 ms/op
                 getUser·p0.90:   2.462 ms/op
                 getUser·p0.95:   2.630 ms/op
                 getUser·p0.99:   3.055 ms/op
                 getUser·p0.999:  16.368 ms/op
                 getUser·p0.9999: 16.983 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16203
  mean =      1.991 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 14735 
    [ 2.500,  3.750) = 1262 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.055 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     16.983 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.125 ms/op
Iteration   1: 3.307 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.142 ms/op
                 listUser·p0.90:   4.053 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.704 ms/op
                 listUser·p0.999:  6.898 ms/op
                 listUser·p0.9999: 7.643 ms/op
                 listUser·p1.00:   7.643 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9665
  mean =      3.307 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 39 
    [2.000, 2.500) = 122 
    [2.500, 3.000) = 3479 
    [3.000, 3.500) = 3098 
    [3.500, 4.000) = 1755 
    [4.000, 4.500) = 824 
    [4.500, 5.000) = 186 
    [5.000, 5.500) = 54 
    [5.500, 6.000) = 28 
    [6.000, 6.500) = 25 
    [6.500, 7.000) = 44 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.053 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.704 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =      7.643 ms/op
     p(99.9990) =      7.643 ms/op
     p(99.9999) =      7.643 ms/op
    p(100.0000) =      7.643 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.285          ops/ms
ClientSimple.existUser                       thrpt         12.237          ops/ms
ClientSimple.getUser                         thrpt         12.405          ops/ms
ClientSimple.listUser                        thrpt          9.348          ops/ms
ClientSimple.createUser                       avgt          2.369           ms/op
ClientSimple.existUser                        avgt          2.097           ms/op
ClientSimple.getUser                          avgt          1.787           ms/op
ClientSimple.listUser                         avgt          3.288           ms/op
ClientSimple.createUser                     sample  13570   2.359 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.503           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.133           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.770           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.383           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.945           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.038           ms/op
ClientSimple.existUser                      sample  15435   2.072 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.634           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.974           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.879           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.174           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.239           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.364           ms/op
ClientSimple.getUser                        sample  16203   1.991 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.575           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.913           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.055           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.368           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.983           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.105           ms/op
ClientSimple.listUser                       sample   9665   3.307 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.192           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.142           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.053           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.704           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.898           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.643           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.643           ms/op

Benchmark result is saved to 1714500727937.json
