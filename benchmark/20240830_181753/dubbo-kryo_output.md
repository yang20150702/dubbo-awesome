# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.057 ops/ms
Iteration   1: 6.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.789 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.648 ops/ms
Iteration   1: 12.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.521 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.963 ops/ms
Iteration   1: 13.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.160 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ops/ms
Iteration   1: 8.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.281 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.081 ms/op
Iteration   1: 2.215 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.069 ms/op
Iteration   1: 2.079 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.503 ±(99.9%) 0.056 ms/op
Iteration   1: 2.110 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.110 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ±(99.9%) 0.090 ms/op
Iteration   1: 3.232 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.232 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.554 ±(99.9%) 0.089 ms/op
Iteration   1: 2.109 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   1.913 ms/op
                 createUser·p0.90:   2.466 ms/op
                 createUser·p0.95:   2.740 ms/op
                 createUser·p0.99:   10.958 ms/op
                 createUser·p0.999:  23.619 ms/op
                 createUser·p0.9999: 24.260 ms/op
                 createUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15214
  mean =      2.109 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13893 
    [ 2.500,  5.000) = 1112 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =     10.958 ms/op
     p(99.9000) =     23.619 ms/op
     p(99.9900) =     24.260 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.057 ±(99.9%) 0.067 ms/op
Iteration   1: 2.214 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.346 ms/op
                 existUser·p0.50:   2.204 ms/op
                 existUser·p0.90:   2.630 ms/op
                 existUser·p0.95:   2.806 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 11.502 ms/op
                 existUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14417
  mean =      2.214 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 283 
    [ 1.250,  2.500) = 11001 
    [ 2.500,  3.750) = 2971 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =     11.387 ms/op
     p(99.9900) =     11.502 ms/op
     p(99.9990) =     11.502 ms/op
     p(99.9999) =     11.502 ms/op
    p(100.0000) =     11.502 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.444 ±(99.9%) 0.084 ms/op
Iteration   1: 1.901 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.574 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.318 ms/op
                 getUser·p0.95:   2.470 ms/op
                 getUser·p0.99:   2.881 ms/op
                 getUser·p0.999:  19.759 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17079
  mean =      1.901 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 16224 
    [ 2.500,  3.750) = 679 
    [ 3.750,  5.000) = 4 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      2.881 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.611 ±(99.9%) 0.134 ms/op
Iteration   1: 3.754 ±(99.9%) 0.265 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   10.128 ms/op
                 listUser·p0.999:  123.664 ms/op
                 listUser·p0.9999: 135.004 ms/op
                 listUser·p1.00:   135.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8521
  mean =      3.754 ±(99.9%) 0.265 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8469 
    [ 12.500,  25.000) = 20 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 29 
    [125.000, 137.500) = 3 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =     10.128 ms/op
     p(99.9000) =    123.664 ms/op
     p(99.9900) =    135.004 ms/op
     p(99.9990) =    135.004 ms/op
     p(99.9999) =    135.004 ms/op
    p(100.0000) =    135.004 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.789          ops/ms
ClientSimple.existUser                       thrpt          12.521          ops/ms
ClientSimple.getUser                         thrpt          13.160          ops/ms
ClientSimple.listUser                        thrpt           8.281          ops/ms
ClientSimple.createUser                       avgt           2.215           ms/op
ClientSimple.existUser                        avgt           2.079           ms/op
ClientSimple.getUser                          avgt           2.110           ms/op
ClientSimple.listUser                         avgt           3.232           ms/op
ClientSimple.createUser                     sample  15214    2.109 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.496           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.913           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.466           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.740           ms/op
ClientSimple.createUser:createUser·p0.99    sample          10.958           ms/op
ClientSimple.createUser:createUser·p0.999   sample          23.619           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          24.260           ms/op
ClientSimple.createUser:createUser·p1.00    sample          24.379           ms/op
ClientSimple.existUser                      sample  14417    2.214 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.346           ms/op
ClientSimple.existUser:existUser·p0.50      sample           2.204           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.630           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.806           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.895           ms/op
ClientSimple.existUser:existUser·p0.999     sample          11.387           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          11.502           ms/op
ClientSimple.existUser:existUser·p1.00      sample          11.502           ms/op
ClientSimple.getUser                        sample  17079    1.901 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.574           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.318           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.470           ms/op
ClientSimple.getUser:getUser·p0.99          sample           2.881           ms/op
ClientSimple.getUser:getUser·p0.999         sample          19.759           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          19.890           ms/op
ClientSimple.getUser:getUser·p1.00          sample          19.890           ms/op
ClientSimple.listUser                       sample   8521    3.754 ± 0.265   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.983           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.031           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample          10.128           ms/op
ClientSimple.listUser:listUser·p0.999       sample         123.664           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         135.004           ms/op
ClientSimple.listUser:listUser·p1.00        sample         135.004           ms/op

Benchmark result is saved to 1725041605961.json
