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
# Warmup Iteration   1: 1.601 ops/ms
Iteration   1: 7.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.197 ops/ms


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
# Warmup Iteration   1: 6.508 ops/ms
Iteration   1: 13.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.266 ops/ms


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
# Warmup Iteration   1: 5.794 ops/ms
Iteration   1: 14.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.038 ops/ms


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
# Warmup Iteration   1: 5.268 ops/ms
Iteration   1: 9.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.110 ops/ms


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.080 ms/op
Iteration   1: 2.296 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.296 ms/op


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
# Warmup Iteration   1: 3.059 ±(99.9%) 0.042 ms/op
Iteration   1: 2.065 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.065 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.059 ms/op
Iteration   1: 2.324 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.324 ms/op


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.079 ms/op
Iteration   1: 3.266 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.266 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.100 ms/op
Iteration   1: 2.142 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   1.907 ms/op
                 createUser·p0.90:   2.716 ms/op
                 createUser·p0.95:   3.045 ms/op
                 createUser·p0.99:   7.905 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 25.166 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14949
  mean =      2.142 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12197 
    [ 2.500,  5.000) = 2577 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      3.045 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.076 ms/op
Iteration   1: 1.852 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   1.714 ms/op
                 existUser·p0.90:   2.253 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   4.313 ms/op
                 existUser·p0.999:  13.959 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17270
  mean =      1.852 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 536 
    [ 1.250,  2.500) = 15934 
    [ 2.500,  3.750) = 606 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.253 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      4.313 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.075 ms/op
Iteration   1: 2.108 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   2.056 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  10.827 ms/op
                 getUser·p0.9999: 11.172 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15155
  mean =      2.108 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 13318 
    [ 2.500,  3.750) = 1459 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =     10.827 ms/op
     p(99.9900) =     11.172 ms/op
     p(99.9990) =     11.223 ms/op
     p(99.9999) =     11.223 ms/op
    p(100.0000) =     11.223 ms/op


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.110 ms/op
Iteration   1: 3.793 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.961 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8460
  mean =      3.793 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 439 
    [ 2.500,  3.750) = 3908 
    [ 3.750,  5.000) = 3818 
    [ 5.000,  6.250) = 155 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.961 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.197          ops/ms
ClientSimple.existUser                       thrpt         13.266          ops/ms
ClientSimple.getUser                         thrpt         14.038          ops/ms
ClientSimple.listUser                        thrpt          9.110          ops/ms
ClientSimple.createUser                       avgt          2.296           ms/op
ClientSimple.existUser                        avgt          2.065           ms/op
ClientSimple.getUser                          avgt          2.324           ms/op
ClientSimple.listUser                         avgt          3.266           ms/op
ClientSimple.createUser                     sample  14949   2.142 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.597           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.907           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.045           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.905           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.283           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.166           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.166           ms/op
ClientSimple.existUser                      sample  17270   1.852 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.698           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.714           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.253           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.313           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.959           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.074           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.074           ms/op
ClientSimple.getUser                        sample  15155   2.108 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.500           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.056           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.670           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.827           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.172           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.223           ms/op
ClientSimple.listUser                       sample   8460   3.793 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.032           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.736           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.961           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.433           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.793           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.793           ms/op

Benchmark result is saved to 1718172771217.json
