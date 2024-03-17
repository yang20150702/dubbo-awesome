# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.294 ops/ms
Iteration   1: 6.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.152 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.010 ops/ms
Iteration   1: 11.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.581 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.616 ops/ms
Iteration   1: 11.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.868 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ops/ms
Iteration   1: 8.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.116 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ±(99.9%) 0.086 ms/op
Iteration   1: 2.136 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.136 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.196 ±(99.9%) 0.055 ms/op
Iteration   1: 1.961 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.961 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.059 ±(99.9%) 0.055 ms/op
Iteration   1: 2.032 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.032 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.022 ±(99.9%) 0.130 ms/op
Iteration   1: 3.233 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.233 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.093 ms/op
Iteration   1: 2.001 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.491 ms/op
                 createUser·p0.50:   1.722 ms/op
                 createUser·p0.90:   2.335 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   8.257 ms/op
                 createUser·p0.999:  25.821 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16026
  mean =      2.001 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14906 
    [ 2.500,  5.000) = 798 
    [ 5.000,  7.500) = 138 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      8.257 ms/op
     p(99.9000) =     25.821 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.015 ±(99.9%) 0.063 ms/op
Iteration   1: 1.978 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.329 ms/op
                 existUser·p0.50:   1.868 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  17.531 ms/op
                 existUser·p0.9999: 17.808 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16154
  mean =      1.978 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 233 
    [ 1.250,  2.500) = 14965 
    [ 2.500,  3.750) = 808 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     17.808 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ±(99.9%) 0.077 ms/op
Iteration   1: 2.227 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   2.101 ms/op
                 getUser·p0.90:   2.816 ms/op
                 getUser·p0.95:   3.035 ms/op
                 getUser·p0.99:   4.031 ms/op
                 getUser·p0.999:  25.723 ms/op
                 getUser·p0.9999: 25.970 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14493
  mean =      2.227 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10241 
    [ 2.500,  5.000) = 4132 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.816 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      4.031 ms/op
     p(99.9000) =     25.723 ms/op
     p(99.9900) =     25.970 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ±(99.9%) 0.109 ms/op
Iteration   1: 3.458 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.687 ms/op
                 listUser·p0.50:   3.482 ms/op
                 listUser·p0.90:   4.556 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   6.330 ms/op
                 listUser·p0.999:  7.186 ms/op
                 listUser·p0.9999: 16.187 ms/op
                 listUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9427
  mean =      3.458 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 1579 
    [ 2.500,  3.750) = 4242 
    [ 3.750,  5.000) = 3080 
    [ 5.000,  6.250) = 404 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.556 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.330 ms/op
     p(99.9000) =      7.186 ms/op
     p(99.9900) =     16.187 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.152          ops/ms
ClientSimple.existUser                       thrpt         11.581          ops/ms
ClientSimple.getUser                         thrpt         11.868          ops/ms
ClientSimple.listUser                        thrpt          8.116          ops/ms
ClientSimple.createUser                       avgt          2.136           ms/op
ClientSimple.existUser                        avgt          1.961           ms/op
ClientSimple.getUser                          avgt          2.032           ms/op
ClientSimple.listUser                         avgt          3.233           ms/op
ClientSimple.createUser                     sample  16026   2.001 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.491           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.722           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.257           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.821           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.952           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.952           ms/op
ClientSimple.existUser                      sample  16154   1.978 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.329           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.868           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.457           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.531           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.808           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.990           ms/op
ClientSimple.getUser                        sample  14493   2.227 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.506           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.101           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.816           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.035           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.031           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.723           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.970           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.985           ms/op
ClientSimple.listUser                       sample   9427   3.458 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.687           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.482           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.556           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.046           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.330           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.186           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.187           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.187           ms/op

Benchmark result is saved to 1710698963269.json
