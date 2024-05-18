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
# Warmup Iteration   1: 1.979 ops/ms
Iteration   1: 7.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.383 ops/ms


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
# Warmup Iteration   1: 5.987 ops/ms
Iteration   1: 11.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.865 ops/ms


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
# Warmup Iteration   1: 6.166 ops/ms
Iteration   1: 14.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.367 ops/ms


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
# Warmup Iteration   1: 5.252 ops/ms
Iteration   1: 9.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.029 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.866 ±(99.9%) 0.057 ms/op
Iteration   1: 2.042 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.042 ms/op


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.054 ms/op
Iteration   1: 1.654 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.654 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.057 ms/op
Iteration   1: 1.909 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.909 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.081 ms/op
Iteration   1: 3.380 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.380 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.597 ±(99.9%) 0.083 ms/op
Iteration   1: 2.286 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.863 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   5.200 ms/op
                 createUser·p0.999:  25.527 ms/op
                 createUser·p0.9999: 26.254 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13974
  mean =      2.286 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10845 
    [ 2.500,  5.000) = 2988 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      5.200 ms/op
     p(99.9000) =     25.527 ms/op
     p(99.9900) =     26.254 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.016 ±(99.9%) 0.066 ms/op
Iteration   1: 1.676 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   1.485 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   4.461 ms/op
                 existUser·p0.999:  21.332 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19234
  mean =      1.676 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18655 
    [ 2.500,  5.000) = 422 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.485 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      4.461 ms/op
     p(99.9000) =     21.332 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.074 ms/op
Iteration   1: 2.124 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.220 ms/op
                 getUser·p0.50:   2.015 ms/op
                 getUser·p0.90:   2.646 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   4.752 ms/op
                 getUser·p0.999:  13.336 ms/op
                 getUser·p0.9999: 13.475 ms/op
                 getUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15044
  mean =      2.124 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 247 
    [ 1.250,  2.500) = 12299 
    [ 2.500,  3.750) = 2281 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.220 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      4.752 ms/op
     p(99.9000) =     13.336 ms/op
     p(99.9900) =     13.475 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 4.419 ±(99.9%) 0.131 ms/op
Iteration   1: 3.434 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.449 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.353 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  17.127 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9312
  mean =      3.434 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 974 
    [ 2.500,  3.750) = 5741 
    [ 3.750,  5.000) = 2435 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.353 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     17.127 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.383          ops/ms
ClientSimple.existUser                       thrpt         11.865          ops/ms
ClientSimple.getUser                         thrpt         14.367          ops/ms
ClientSimple.listUser                        thrpt          9.029          ops/ms
ClientSimple.createUser                       avgt          2.042           ms/op
ClientSimple.existUser                        avgt          1.654           ms/op
ClientSimple.getUser                          avgt          1.909           ms/op
ClientSimple.listUser                         avgt          3.380           ms/op
ClientSimple.createUser                     sample  13974   2.286 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.604           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.200           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.527           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.254           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.345           ms/op
ClientSimple.existUser                      sample  19234   1.676 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.675           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.485           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.461           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.332           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.365           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.365           ms/op
ClientSimple.getUser                        sample  15044   2.124 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.220           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.015           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.752           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.336           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.475           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.533           ms/op
ClientSimple.listUser                       sample   9312   3.434 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.174           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.449           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.137           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.353           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.800           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.127           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.203           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.203           ms/op

Benchmark result is saved to 1716055886440.json
