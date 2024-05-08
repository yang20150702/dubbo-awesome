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
# Warmup Iteration   1: 1.752 ops/ms
Iteration   1: 6.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.253 ops/ms


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
# Warmup Iteration   1: 5.864 ops/ms
Iteration   1: 10.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.955 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ops/ms
Iteration   1: 13.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.465 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ops/ms
Iteration   1: 8.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.081 ops/ms


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.061 ms/op
Iteration   1: 2.286 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.286 ms/op


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
# Warmup Iteration   1: 3.132 ±(99.9%) 0.060 ms/op
Iteration   1: 1.689 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.689 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.049 ms/op
Iteration   1: 2.076 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.076 ms/op


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.091 ms/op
Iteration   1: 3.408 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.408 ms/op


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
# Warmup Iteration   1: 3.462 ±(99.9%) 0.083 ms/op
Iteration   1: 2.236 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   2.048 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   7.827 ms/op
                 createUser·p0.999:  13.178 ms/op
                 createUser·p0.9999: 14.178 ms/op
                 createUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14330
  mean =      2.236 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 12453 
    [ 2.500,  3.750) = 1346 
    [ 3.750,  5.000) = 201 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      7.827 ms/op
     p(99.9000) =     13.178 ms/op
     p(99.9900) =     14.178 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.148 ±(99.9%) 0.110 ms/op
Iteration   1: 2.115 ±(99.9%) 0.095 ms/op
                 existUser·p0.00:   0.302 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   4.529 ms/op
                 existUser·p0.999:  77.187 ms/op
                 existUser·p0.9999: 81.002 ms/op
                 existUser·p1.00:   81.002 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15112
  mean =      2.115 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14973 
    [ 5.000, 10.000) = 75 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 29 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 2 
    [75.000, 80.000) = 26 
    [80.000, 85.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.529 ms/op
     p(99.9000) =     77.187 ms/op
     p(99.9900) =     81.002 ms/op
     p(99.9990) =     81.002 ms/op
     p(99.9999) =     81.002 ms/op
    p(100.0000) =     81.002 ms/op


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
# Warmup Iteration   1: 3.495 ±(99.9%) 0.116 ms/op
Iteration   1: 1.956 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   1.866 ms/op
                 getUser·p0.90:   2.257 ms/op
                 getUser·p0.95:   2.449 ms/op
                 getUser·p0.99:   3.240 ms/op
                 getUser·p0.999:  15.122 ms/op
                 getUser·p0.9999: 15.211 ms/op
                 getUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16481
  mean =      1.956 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 15700 
    [ 2.500,  3.750) = 615 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      3.240 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     15.211 ms/op
     p(99.9990) =     15.254 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.125 ms/op
Iteration   1: 3.603 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.287 ms/op
                 listUser·p0.99:   7.801 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8871
  mean =      3.603 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1038 
    [ 2.500,  3.750) = 4436 
    [ 3.750,  5.000) = 2842 
    [ 5.000,  6.250) = 303 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      5.287 ms/op
     p(99.0000) =      7.801 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.253          ops/ms
ClientSimple.existUser                       thrpt         10.955          ops/ms
ClientSimple.getUser                         thrpt         13.465          ops/ms
ClientSimple.listUser                        thrpt          8.081          ops/ms
ClientSimple.createUser                       avgt          2.286           ms/op
ClientSimple.existUser                        avgt          1.689           ms/op
ClientSimple.getUser                          avgt          2.076           ms/op
ClientSimple.listUser                         avgt          3.408           ms/op
ClientSimple.createUser                     sample  14330   2.236 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.801           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.048           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.827           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.178           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.178           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.320           ms/op
ClientSimple.existUser                      sample  15112   2.115 ± 0.095   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.302           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.829           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.529           ms/op
ClientSimple.existUser:existUser·p0.999     sample         77.187           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         81.002           ms/op
ClientSimple.existUser:existUser·p1.00      sample         81.002           ms/op
ClientSimple.getUser                        sample  16481   1.956 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.698           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.866           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.257           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.240           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.122           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.211           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.254           ms/op
ClientSimple.listUser                       sample   8871   3.603 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.806           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.287           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.801           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.368           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.958           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.958           ms/op

Benchmark result is saved to 1715148668906.json
