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
# Warmup Iteration   1: 1.814 ops/ms
Iteration   1: 6.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.934 ops/ms


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
# Warmup Iteration   1: 6.074 ops/ms
Iteration   1: 12.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.335 ops/ms


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
# Warmup Iteration   1: 5.371 ops/ms
Iteration   1: 11.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.058 ops/ms


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
# Warmup Iteration   1: 4.660 ops/ms
Iteration   1: 8.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.137 ops/ms


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.068 ms/op
Iteration   1: 2.179 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.179 ms/op


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
# Warmup Iteration   1: 3.263 ±(99.9%) 0.048 ms/op
Iteration   1: 1.979 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.979 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.047 ms/op
Iteration   1: 2.035 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.035 ms/op


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
# Warmup Iteration   1: 5.046 ±(99.9%) 0.108 ms/op
Iteration   1: 3.335 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.335 ms/op


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.105 ms/op
Iteration   1: 2.381 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.456 ms/op
                 createUser·p0.50:   2.269 ms/op
                 createUser·p0.90:   2.884 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  15.363 ms/op
                 createUser·p0.9999: 19.285 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13477
  mean =      2.381 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9721 
    [ 2.500,  5.000) = 3541 
    [ 5.000,  7.500) = 109 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     15.363 ms/op
     p(99.9900) =     19.285 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.166 ±(99.9%) 0.079 ms/op
Iteration   1: 1.684 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   1.608 ms/op
                 existUser·p0.90:   2.007 ms/op
                 existUser·p0.95:   2.216 ms/op
                 existUser·p0.99:   3.036 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18994
  mean =      1.684 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1121 
    [ 1.250,  2.500) = 17385 
    [ 2.500,  3.750) = 383 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      1.608 ms/op
     p(90.0000) =      2.007 ms/op
     p(95.0000) =      2.216 ms/op
     p(99.0000) =      3.036 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.074 ms/op
Iteration   1: 1.818 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   1.692 ms/op
                 getUser·p0.90:   2.449 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   3.269 ms/op
                 getUser·p0.999:  10.355 ms/op
                 getUser·p0.9999: 10.514 ms/op
                 getUser·p1.00:   10.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17572
  mean =      1.818 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 8 
    [ 1.000,  2.000) = 14703 
    [ 2.000,  3.000) = 2477 
    [ 3.000,  4.000) = 317 
    [ 4.000,  5.000) = 8 
    [ 5.000,  6.000) = 17 
    [ 6.000,  7.000) = 6 
    [ 7.000,  8.000) = 3 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.269 ms/op
     p(99.9000) =     10.355 ms/op
     p(99.9900) =     10.514 ms/op
     p(99.9990) =     10.551 ms/op
     p(99.9999) =     10.551 ms/op
    p(100.0000) =     10.551 ms/op


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
# Warmup Iteration   1: 4.302 ±(99.9%) 0.121 ms/op
Iteration   1: 3.115 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.713 ms/op
                 listUser·p0.999:  26.838 ms/op
                 listUser·p0.9999: 28.404 ms/op
                 listUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10321
  mean =      3.115 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1307 
    [ 2.500,  5.000) = 8855 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.713 ms/op
     p(99.9000) =     26.838 ms/op
     p(99.9900) =     28.404 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.934          ops/ms
ClientSimple.existUser                       thrpt         12.335          ops/ms
ClientSimple.getUser                         thrpt         11.058          ops/ms
ClientSimple.listUser                        thrpt          8.137          ops/ms
ClientSimple.createUser                       avgt          2.179           ms/op
ClientSimple.existUser                        avgt          1.979           ms/op
ClientSimple.getUser                          avgt          2.035           ms/op
ClientSimple.listUser                         avgt          3.335           ms/op
ClientSimple.createUser                     sample  13477   2.381 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.456           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.142           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.709           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.363           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.285           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.234           ms/op
ClientSimple.existUser                      sample  18994   1.684 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.759           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.608           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.007           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.036           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.714           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.451           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.451           ms/op
ClientSimple.getUser                        sample  17572   1.818 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.800           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.692           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.269           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.355           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.514           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.551           ms/op
ClientSimple.listUser                       sample  10321   3.115 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.701           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.875           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.713           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.838           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.404           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.410           ms/op

Benchmark result is saved to 1714479269097.json
