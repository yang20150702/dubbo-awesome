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
# Warmup Iteration   1: 1.733 ops/ms
Iteration   1: 7.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.301 ops/ms


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
# Warmup Iteration   1: 5.642 ops/ms
Iteration   1: 11.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.872 ops/ms


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
# Warmup Iteration   1: 5.923 ops/ms
Iteration   1: 13.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.108 ops/ms


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
# Warmup Iteration   1: 5.634 ops/ms
Iteration   1: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.590 ops/ms


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.081 ms/op
Iteration   1: 2.157 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.157 ms/op


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
# Warmup Iteration   1: 3.621 ±(99.9%) 0.064 ms/op
Iteration   1: 1.796 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.796 ms/op


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
# Warmup Iteration   1: 3.413 ±(99.9%) 0.063 ms/op
Iteration   1: 2.027 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.027 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.097 ms/op
Iteration   1: 3.357 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.357 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.121 ms/op
Iteration   1: 2.091 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   1.868 ms/op
                 createUser·p0.90:   2.384 ms/op
                 createUser·p0.95:   2.773 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 20.129 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15298
  mean =      2.091 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14223 
    [ 2.500,  5.000) = 673 
    [ 5.000,  7.500) = 263 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     20.129 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 2.900 ±(99.9%) 0.062 ms/op
Iteration   1: 1.958 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   3.178 ms/op
                 existUser·p0.999:  25.526 ms/op
                 existUser·p0.9999: 26.218 ms/op
                 existUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16318
  mean =      1.958 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15449 
    [ 2.500,  5.000) = 795 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.178 ms/op
     p(99.9000) =     25.526 ms/op
     p(99.9900) =     26.218 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.085 ms/op
Iteration   1: 2.040 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.785 ms/op
                 getUser·p0.99:   4.994 ms/op
                 getUser·p0.999:  14.096 ms/op
                 getUser·p0.9999: 14.379 ms/op
                 getUser·p1.00:   14.434 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15671
  mean =      2.040 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 13979 
    [ 2.500,  3.750) = 1288 
    [ 3.750,  5.000) = 127 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      4.994 ms/op
     p(99.9000) =     14.096 ms/op
     p(99.9900) =     14.379 ms/op
     p(99.9990) =     14.434 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 4.469 ±(99.9%) 0.127 ms/op
Iteration   1: 3.552 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.473 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9016
  mean =      3.552 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 942 
    [ 2.500,  3.750) = 4780 
    [ 3.750,  5.000) = 2971 
    [ 5.000,  6.250) = 168 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.301          ops/ms
ClientSimple.existUser                       thrpt         11.872          ops/ms
ClientSimple.getUser                         thrpt         13.108          ops/ms
ClientSimple.listUser                        thrpt          9.590          ops/ms
ClientSimple.createUser                       avgt          2.157           ms/op
ClientSimple.existUser                        avgt          1.796           ms/op
ClientSimple.getUser                          avgt          2.027           ms/op
ClientSimple.listUser                         avgt          3.357           ms/op
ClientSimple.createUser                     sample  15298   2.091 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.485           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.868           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.384           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.315           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.957           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.129           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.251           ms/op
ClientSimple.existUser                      sample  16318   1.958 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.492           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.876           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.178           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.526           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.218           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.280           ms/op
ClientSimple.getUser                        sample  15671   2.040 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.834           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.785           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.994           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.096           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.379           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.434           ms/op
ClientSimple.listUser                       sample   9016   3.552 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.184           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.473           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.584           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.333           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.530           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.530           ms/op

Benchmark result is saved to 1720441062845.json
