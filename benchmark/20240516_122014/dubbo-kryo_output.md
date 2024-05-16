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
# Warmup Iteration   1: 2.081 ops/ms
Iteration   1: 6.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.661 ops/ms


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
# Warmup Iteration   1: 6.661 ops/ms
Iteration   1: 14.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.005 ops/ms


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
# Warmup Iteration   1: 4.260 ops/ms
Iteration   1: 13.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.277 ops/ms


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
# Warmup Iteration   1: 4.639 ops/ms
Iteration   1: 8.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.402 ops/ms


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.065 ms/op
Iteration   1: 2.038 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.038 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.041 ms/op
Iteration   1: 1.871 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.871 ms/op


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
# Warmup Iteration   1: 3.490 ±(99.9%) 0.063 ms/op
Iteration   1: 2.194 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.194 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.092 ms/op
Iteration   1: 4.075 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.075 ms/op


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
# Warmup Iteration   1: 3.601 ±(99.9%) 0.097 ms/op
Iteration   1: 2.073 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.817 ms/op
                 createUser·p0.99:   5.519 ms/op
                 createUser·p0.999:  15.607 ms/op
                 createUser·p0.9999: 17.936 ms/op
                 createUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15423
  mean =      2.073 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 13869 
    [ 2.500,  3.750) = 1035 
    [ 3.750,  5.000) = 184 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.817 ms/op
     p(99.0000) =      5.519 ms/op
     p(99.9000) =     15.607 ms/op
     p(99.9900) =     17.936 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.070 ms/op
Iteration   1: 1.922 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.330 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  19.536 ms/op
                 existUser·p0.9999: 20.916 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16810
  mean =      1.922 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16101 
    [ 2.500,  5.000) = 631 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      3.391 ms/op
     p(99.9000) =     19.536 ms/op
     p(99.9900) =     20.916 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.082 ms/op
Iteration   1: 2.311 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.241 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   5.064 ms/op
                 getUser·p0.999:  16.625 ms/op
                 getUser·p0.9999: 17.393 ms/op
                 getUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14038
  mean =      2.311 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 10573 
    [ 2.500,  3.750) = 3141 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.241 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      5.064 ms/op
     p(99.9000) =     16.625 ms/op
     p(99.9900) =     17.393 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.145 ms/op
Iteration   1: 3.741 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.476 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   5.395 ms/op
                 listUser·p0.999:  9.232 ms/op
                 listUser·p0.9999: 10.060 ms/op
                 listUser·p1.00:   10.060 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8545
  mean =      3.741 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 41 
    [ 2.000,  3.000) = 976 
    [ 3.000,  4.000) = 5135 
    [ 4.000,  5.000) = 2153 
    [ 5.000,  6.000) = 192 
    [ 6.000,  7.000) = 15 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 11 
    [ 9.000, 10.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.476 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      5.395 ms/op
     p(99.9000) =      9.232 ms/op
     p(99.9900) =     10.060 ms/op
     p(99.9990) =     10.060 ms/op
     p(99.9999) =     10.060 ms/op
    p(100.0000) =     10.060 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.661          ops/ms
ClientSimple.existUser                       thrpt         14.005          ops/ms
ClientSimple.getUser                         thrpt         13.277          ops/ms
ClientSimple.listUser                        thrpt          8.402          ops/ms
ClientSimple.createUser                       avgt          2.038           ms/op
ClientSimple.existUser                        avgt          1.871           ms/op
ClientSimple.getUser                          avgt          2.194           ms/op
ClientSimple.listUser                         avgt          4.075           ms/op
ClientSimple.createUser                     sample  15423   2.073 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.597           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.817           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.519           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.607           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.936           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.416           ms/op
ClientSimple.existUser                      sample  16810   1.922 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.330           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.391           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.536           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.916           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.939           ms/op
ClientSimple.getUser                        sample  14038   2.311 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.745           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.241           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.064           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.625           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.393           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.433           ms/op
ClientSimple.listUser                       sample   8545   3.741 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.020           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.476           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.395           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.232           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.060           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.060           ms/op

Benchmark result is saved to 1715861775214.json
