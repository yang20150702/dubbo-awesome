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
# Warmup Iteration   1: 1.533 ops/ms
Iteration   1: 6.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.752 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.944 ops/ms
Iteration   1: 11.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.387 ops/ms


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
# Warmup Iteration   1: 4.887 ops/ms
Iteration   1: 11.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.112 ops/ms


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
# Warmup Iteration   1: 3.706 ops/ms
Iteration   1: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.611 ops/ms


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.077 ms/op
Iteration   1: 2.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.037 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.056 ms/op
Iteration   1: 1.803 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.803 ms/op


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
# Warmup Iteration   1: 3.337 ±(99.9%) 0.057 ms/op
Iteration   1: 2.152 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.152 ms/op


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
# Warmup Iteration   1: 4.954 ±(99.9%) 0.108 ms/op
Iteration   1: 3.316 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.316 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.084 ms/op
Iteration   1: 2.255 ±(99.9%) 0.066 ms/op
                 createUser·p0.00:   0.500 ms/op
                 createUser·p0.50:   2.046 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   2.970 ms/op
                 createUser·p0.99:   7.950 ms/op
                 createUser·p0.999:  40.370 ms/op
                 createUser·p0.9999: 60.239 ms/op
                 createUser·p1.00:   60.293 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14160
  mean =      2.255 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13963 
    [ 5.000, 10.000) = 65 
    [10.000, 15.000) = 78 
    [15.000, 20.000) = 14 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 13 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 6 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      7.950 ms/op
     p(99.9000) =     40.370 ms/op
     p(99.9900) =     60.239 ms/op
     p(99.9990) =     60.293 ms/op
     p(99.9999) =     60.293 ms/op
    p(100.0000) =     60.293 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.064 ms/op
Iteration   1: 1.955 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   1.897 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  13.674 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16374
  mean =      1.955 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 454 
    [ 1.250,  2.500) = 14550 
    [ 2.500,  3.750) = 1230 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      1.897 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =     13.674 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.077 ms/op
Iteration   1: 1.850 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   1.726 ms/op
                 getUser·p0.90:   2.290 ms/op
                 getUser·p0.95:   2.503 ms/op
                 getUser·p0.99:   3.339 ms/op
                 getUser·p0.999:  12.616 ms/op
                 getUser·p0.9999: 12.870 ms/op
                 getUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17283
  mean =      1.850 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 16330 
    [ 2.500,  3.750) = 734 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.339 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     12.870 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.846 ±(99.9%) 0.124 ms/op
Iteration   1: 3.478 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.314 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   9.766 ms/op
                 listUser·p0.999:  18.868 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9193
  mean =      3.478 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1386 
    [ 2.500,  3.750) = 4850 
    [ 3.750,  5.000) = 2526 
    [ 5.000,  6.250) = 202 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      9.766 ms/op
     p(99.9000) =     18.868 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.752          ops/ms
ClientSimple.existUser                       thrpt         11.387          ops/ms
ClientSimple.getUser                         thrpt         11.112          ops/ms
ClientSimple.listUser                        thrpt          8.611          ops/ms
ClientSimple.createUser                       avgt          2.037           ms/op
ClientSimple.existUser                        avgt          1.803           ms/op
ClientSimple.getUser                          avgt          2.152           ms/op
ClientSimple.listUser                         avgt          3.316           ms/op
ClientSimple.createUser                     sample  14160   2.255 ± 0.066   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.500           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.046           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.970           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.950           ms/op
ClientSimple.createUser:createUser·p0.999   sample         40.370           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         60.239           ms/op
ClientSimple.createUser:createUser·p1.00    sample         60.293           ms/op
ClientSimple.existUser                      sample  16374   1.955 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.434           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.897           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.375           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.674           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.074           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.189           ms/op
ClientSimple.getUser                        sample  17283   1.850 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.804           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.726           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.290           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.339           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.616           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.870           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.894           ms/op
ClientSimple.listUser                       sample   9193   3.478 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.393           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.314           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.766           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.868           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.940           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.940           ms/op

Benchmark result is saved to 1714068673375.json
