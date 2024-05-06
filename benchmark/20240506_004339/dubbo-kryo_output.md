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
# Warmup Iteration   1: 1.839 ops/ms
Iteration   1: 7.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.224 ops/ms


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
# Warmup Iteration   1: 5.703 ops/ms
Iteration   1: 11.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.940 ops/ms


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
# Warmup Iteration   1: 5.668 ops/ms
Iteration   1: 12.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.106 ops/ms


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
# Warmup Iteration   1: 3.943 ops/ms
Iteration   1: 8.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.560 ops/ms


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.083 ms/op
Iteration   1: 2.054 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.054 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.052 ms/op
Iteration   1: 1.926 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.926 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.053 ms/op
Iteration   1: 2.057 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.057 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.109 ms/op
Iteration   1: 3.329 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.329 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.115 ms/op
Iteration   1: 2.549 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.472 ms/op
                 createUser·p0.50:   2.294 ms/op
                 createUser·p0.90:   3.232 ms/op
                 createUser·p0.95:   3.964 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  11.321 ms/op
                 createUser·p0.9999: 12.504 ms/op
                 createUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12703
  mean =      2.549 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 8095 
    [ 2.500,  3.750) = 3844 
    [ 3.750,  5.000) = 281 
    [ 5.000,  6.250) = 165 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.294 ms/op
     p(90.0000) =      3.232 ms/op
     p(95.0000) =      3.964 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     12.504 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


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
# Warmup Iteration   1: 3.028 ±(99.9%) 0.066 ms/op
Iteration   1: 1.745 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.263 ms/op
                 existUser·p0.50:   1.571 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.318 ms/op
                 existUser·p0.99:   3.164 ms/op
                 existUser·p0.999:  25.285 ms/op
                 existUser·p0.9999: 25.477 ms/op
                 existUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18370
  mean =      1.745 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17903 
    [ 2.500,  5.000) = 383 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.263 ms/op
     p(50.0000) =      1.571 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.318 ms/op
     p(99.0000) =      3.164 ms/op
     p(99.9000) =     25.285 ms/op
     p(99.9900) =     25.477 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 3.330 ±(99.9%) 0.085 ms/op
Iteration   1: 1.904 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   1.802 ms/op
                 getUser·p0.90:   2.445 ms/op
                 getUser·p0.95:   2.654 ms/op
                 getUser·p0.99:   3.675 ms/op
                 getUser·p0.999:  18.809 ms/op
                 getUser·p0.9999: 19.977 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16776
  mean =      1.904 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15389 
    [ 2.500,  5.000) = 1278 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.675 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     19.977 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 5.072 ±(99.9%) 0.300 ms/op
Iteration   1: 3.548 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.469 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.354 ms/op
                 listUser·p0.999:  26.804 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9008
  mean =      3.548 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 769 
    [ 2.500,  5.000) = 7931 
    [ 5.000,  7.500) = 238 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.354 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.224          ops/ms
ClientSimple.existUser                       thrpt         11.940          ops/ms
ClientSimple.getUser                         thrpt         12.106          ops/ms
ClientSimple.listUser                        thrpt          8.560          ops/ms
ClientSimple.createUser                       avgt          2.054           ms/op
ClientSimple.existUser                        avgt          1.926           ms/op
ClientSimple.getUser                          avgt          2.057           ms/op
ClientSimple.listUser                         avgt          3.329           ms/op
ClientSimple.createUser                     sample  12703   2.549 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.472           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.294           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.232           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.964           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.634           ms/op
ClientSimple.createUser:createUser·p0.999   sample         11.321           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.504           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.894           ms/op
ClientSimple.existUser                      sample  18370   1.745 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.263           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.571           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.164           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.285           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.477           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.559           ms/op
ClientSimple.getUser                        sample  16776   1.904 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.454           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.802           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.675           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.809           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.977           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.021           ms/op
ClientSimple.listUser                       sample   9008   3.548 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.067           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.469           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.354           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.804           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.197           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.197           ms/op

Benchmark result is saved to 1714955959051.json
