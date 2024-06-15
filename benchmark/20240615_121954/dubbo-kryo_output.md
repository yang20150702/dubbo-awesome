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
# Warmup Iteration   1: 1.794 ops/ms
Iteration   1: 6.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.853 ops/ms


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
# Warmup Iteration   1: 5.050 ops/ms
Iteration   1: 11.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.915 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.046 ops/ms
Iteration   1: 11.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.675 ops/ms


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
# Warmup Iteration   1: 5.064 ops/ms
Iteration   1: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.846 ops/ms


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.075 ms/op
Iteration   1: 2.234 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.234 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.048 ms/op
Iteration   1: 1.702 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.702 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.057 ms/op
Iteration   1: 1.837 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.837 ms/op


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.081 ms/op
Iteration   1: 3.625 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.625 ms/op


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
# Warmup Iteration   1: 3.271 ±(99.9%) 0.079 ms/op
Iteration   1: 2.001 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.517 ms/op
                 createUser·p0.50:   1.843 ms/op
                 createUser·p0.90:   2.335 ms/op
                 createUser·p0.95:   2.548 ms/op
                 createUser·p0.99:   8.588 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 21.555 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15980
  mean =      2.001 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15061 
    [ 2.500,  5.000) = 656 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      8.588 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     21.555 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 2.895 ±(99.9%) 0.065 ms/op
Iteration   1: 1.800 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.175 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  17.662 ms/op
                 existUser·p0.9999: 17.971 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17776
  mean =      1.800 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 958 
    [ 1.250,  2.500) = 16217 
    [ 2.500,  3.750) = 414 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     17.971 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 3.176 ±(99.9%) 0.074 ms/op
Iteration   1: 2.079 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.470 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  19.792 ms/op
                 getUser·p0.9999: 20.003 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15535
  mean =      2.079 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13277 
    [ 2.500,  5.000) = 2085 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     20.003 ms/op
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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.157 ms/op
Iteration   1: 3.462 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.645 ms/op
                 listUser·p0.50:   3.387 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.264 ms/op
                 listUser·p0.999:  8.598 ms/op
                 listUser·p0.9999: 9.191 ms/op
                 listUser·p1.00:   9.191 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9240
  mean =      3.462 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 15 
    [ 1.000,  2.000) = 157 
    [ 2.000,  3.000) = 2441 
    [ 3.000,  4.000) = 4768 
    [ 4.000,  5.000) = 1553 
    [ 5.000,  6.000) = 165 
    [ 6.000,  7.000) = 90 
    [ 7.000,  8.000) = 14 
    [ 8.000,  9.000) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.264 ms/op
     p(99.9000) =      8.598 ms/op
     p(99.9900) =      9.191 ms/op
     p(99.9990) =      9.191 ms/op
     p(99.9999) =      9.191 ms/op
    p(100.0000) =      9.191 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.853          ops/ms
ClientSimple.existUser                       thrpt         11.915          ops/ms
ClientSimple.getUser                         thrpt         11.675          ops/ms
ClientSimple.listUser                        thrpt          7.846          ops/ms
ClientSimple.createUser                       avgt          2.234           ms/op
ClientSimple.existUser                        avgt          1.702           ms/op
ClientSimple.getUser                          avgt          1.837           ms/op
ClientSimple.listUser                         avgt          3.625           ms/op
ClientSimple.createUser                     sample  15980   2.001 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.517           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.843           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.548           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.588           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.825           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.555           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.594           ms/op
ClientSimple.existUser                      sample  17776   1.800 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.175           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.932           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.662           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.971           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.022           ms/op
ClientSimple.getUser                        sample  15535   2.079 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.470           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.431           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.792           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.003           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.021           ms/op
ClientSimple.listUser                       sample   9240   3.462 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.645           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.387           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.264           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.598           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.191           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.191           ms/op

Benchmark result is saved to 1718453737961.json
