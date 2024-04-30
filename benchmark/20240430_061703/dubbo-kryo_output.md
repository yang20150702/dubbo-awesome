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
# Warmup Iteration   1: 1.982 ops/ms
Iteration   1: 6.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.575 ops/ms


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
# Warmup Iteration   1: 5.870 ops/ms
Iteration   1: 11.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.949 ops/ms


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
# Warmup Iteration   1: 5.062 ops/ms
Iteration   1: 11.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.662 ops/ms


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
# Warmup Iteration   1: 3.903 ops/ms
Iteration   1: 8.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.186 ops/ms


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.071 ms/op
Iteration   1: 2.204 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.204 ms/op


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
# Warmup Iteration   1: 3.243 ±(99.9%) 0.064 ms/op
Iteration   1: 1.923 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.923 ms/op


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
# Warmup Iteration   1: 3.621 ±(99.9%) 0.069 ms/op
Iteration   1: 2.365 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.365 ms/op


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
# Warmup Iteration   1: 4.652 ±(99.9%) 0.113 ms/op
Iteration   1: 3.487 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.487 ms/op


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.108 ms/op
Iteration   1: 2.222 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.736 ms/op
                 createUser·p0.99:   11.731 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 20.965 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14381
  mean =      2.222 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12621 
    [ 2.500,  5.000) = 1517 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     20.965 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 2.944 ±(99.9%) 0.083 ms/op
Iteration   1: 2.107 ±(99.9%) 0.062 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   1.939 ms/op
                 existUser·p0.90:   2.593 ms/op
                 existUser·p0.95:   2.844 ms/op
                 existUser·p0.99:   6.146 ms/op
                 existUser·p0.999:  49.970 ms/op
                 existUser·p0.9999: 59.504 ms/op
                 existUser·p1.00:   59.572 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15173
  mean =      2.107 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15014 
    [ 5.000, 10.000) = 76 
    [10.000, 15.000) = 39 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.844 ms/op
     p(99.0000) =      6.146 ms/op
     p(99.9000) =     49.970 ms/op
     p(99.9900) =     59.504 ms/op
     p(99.9990) =     59.572 ms/op
     p(99.9999) =     59.572 ms/op
    p(100.0000) =     59.572 ms/op


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.090 ms/op
Iteration   1: 2.385 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.310 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.848 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 13.205 ms/op
                 getUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13431
  mean =      2.385 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 8593 
    [ 2.500,  3.750) = 4534 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.848 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.205 ms/op
     p(99.9990) =     13.238 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


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
# Warmup Iteration   1: 5.329 ±(99.9%) 0.414 ms/op
Iteration   1: 3.726 ±(99.9%) 0.094 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.252 ms/op
                 listUser·p0.999:  47.017 ms/op
                 listUser·p0.9999: 48.628 ms/op
                 listUser·p1.00:   48.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8578
  mean =      3.726 ±(99.9%) 0.094 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8309 
    [ 5.000, 10.000) = 224 
    [10.000, 15.000) = 11 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.252 ms/op
     p(99.9000) =     47.017 ms/op
     p(99.9900) =     48.628 ms/op
     p(99.9990) =     48.628 ms/op
     p(99.9999) =     48.628 ms/op
    p(100.0000) =     48.628 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.575          ops/ms
ClientSimple.existUser                       thrpt         11.949          ops/ms
ClientSimple.getUser                         thrpt         11.662          ops/ms
ClientSimple.listUser                        thrpt          8.186          ops/ms
ClientSimple.createUser                       avgt          2.204           ms/op
ClientSimple.existUser                        avgt          1.923           ms/op
ClientSimple.getUser                          avgt          2.365           ms/op
ClientSimple.listUser                         avgt          3.487           ms/op
ClientSimple.createUser                     sample  14381   2.222 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.550           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.736           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.731           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.153           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.965           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.266           ms/op
ClientSimple.existUser                      sample  15173   2.107 ± 0.062   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.473           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.939           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.844           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.146           ms/op
ClientSimple.existUser:existUser·p0.999     sample         49.970           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         59.504           ms/op
ClientSimple.existUser:existUser·p1.00      sample         59.572           ms/op
ClientSimple.getUser                        sample  13431   2.385 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.695           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.006           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.269           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.848           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.058           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.205           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.238           ms/op
ClientSimple.listUser                       sample   8578   3.726 ± 0.094   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.719           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.572           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.252           ms/op
ClientSimple.listUser:listUser·p0.999       sample         47.017           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         48.628           ms/op
ClientSimple.listUser:listUser·p1.00        sample         48.628           ms/op

Benchmark result is saved to 1714457514158.json
