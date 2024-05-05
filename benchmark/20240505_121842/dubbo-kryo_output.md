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
Iteration   1: 8.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.101 ops/ms


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
# Warmup Iteration   1: 6.073 ops/ms
Iteration   1: 12.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.502 ops/ms


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
# Warmup Iteration   1: 5.531 ops/ms
Iteration   1: 12.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.673 ops/ms


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
# Warmup Iteration   1: 4.710 ops/ms
Iteration   1: 8.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.383 ops/ms


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.059 ms/op
Iteration   1: 2.234 ±(99.9%) 0.022 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.308 ±(99.9%) 0.056 ms/op
Iteration   1: 1.904 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.904 ms/op


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
# Warmup Iteration   1: 3.266 ±(99.9%) 0.060 ms/op
Iteration   1: 1.862 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.862 ms/op


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
# Warmup Iteration   1: 5.205 ±(99.9%) 0.099 ms/op
Iteration   1: 3.442 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.442 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.103 ms/op
Iteration   1: 2.140 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   1.952 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.802 ms/op
                 createUser·p0.99:   4.621 ms/op
                 createUser·p0.999:  19.002 ms/op
                 createUser·p0.9999: 19.775 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15097
  mean =      2.140 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 13052 
    [ 2.500,  3.750) = 1799 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.621 ms/op
     p(99.9000) =     19.002 ms/op
     p(99.9900) =     19.775 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.068 ms/op
Iteration   1: 1.888 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.308 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.806 ms/op
                 existUser·p0.99:   3.187 ms/op
                 existUser·p0.999:  18.514 ms/op
                 existUser·p0.9999: 18.862 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16950
  mean =      1.888 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 310 
    [ 1.250,  2.500) = 14722 
    [ 2.500,  3.750) = 1859 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.187 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     18.862 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.087 ms/op
Iteration   1: 1.940 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   1.772 ms/op
                 getUser·p0.90:   2.480 ms/op
                 getUser·p0.95:   2.626 ms/op
                 getUser·p0.99:   3.466 ms/op
                 getUser·p0.999:  11.789 ms/op
                 getUser·p0.9999: 12.324 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16475
  mean =      1.940 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 14860 
    [ 2.500,  3.750) = 1410 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.480 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.466 ms/op
     p(99.9000) =     11.789 ms/op
     p(99.9900) =     12.324 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.138 ms/op
Iteration   1: 3.335 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.203 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.387 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  14.234 ms/op
                 listUser·p0.9999: 14.975 ms/op
                 listUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9689
  mean =      3.335 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1412 
    [ 2.500,  3.750) = 5464 
    [ 3.750,  5.000) = 2560 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.387 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     14.234 ms/op
     p(99.9900) =     14.975 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.101          ops/ms
ClientSimple.existUser                       thrpt         12.502          ops/ms
ClientSimple.getUser                         thrpt         12.673          ops/ms
ClientSimple.listUser                        thrpt          8.383          ops/ms
ClientSimple.createUser                       avgt          2.234           ms/op
ClientSimple.existUser                        avgt          1.904           ms/op
ClientSimple.getUser                          avgt          1.862           ms/op
ClientSimple.listUser                         avgt          3.442           ms/op
ClientSimple.createUser                     sample  15097   2.140 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.980           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.952           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.621           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.002           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.775           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.792           ms/op
ClientSimple.existUser                      sample  16950   1.888 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.308           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.690           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.806           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.187           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.514           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.862           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.907           ms/op
ClientSimple.getUser                        sample  16475   1.940 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.759           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.772           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.480           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.466           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.789           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.324           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.419           ms/op
ClientSimple.listUser                       sample   9689   3.335 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.945           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.203           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.387           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.922           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.234           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.975           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.975           ms/op

Benchmark result is saved to 1714911255612.json
