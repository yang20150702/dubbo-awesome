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
# Warmup Iteration   1: 1.708 ops/ms
Iteration   1: 7.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.644 ops/ms


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
# Warmup Iteration   1: 5.748 ops/ms
Iteration   1: 12.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.141 ops/ms


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
# Warmup Iteration   1: 6.313 ops/ms
Iteration   1: 14.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.887 ops/ms


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
# Warmup Iteration   1: 4.669 ops/ms
Iteration   1: 8.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.521 ops/ms


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
# Warmup Iteration   1: 4.918 ±(99.9%) 0.085 ms/op
Iteration   1: 2.543 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.543 ms/op


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
# Warmup Iteration   1: 3.538 ±(99.9%) 0.051 ms/op
Iteration   1: 2.079 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.079 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.060 ms/op
Iteration   1: 1.770 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.770 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.098 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.000 ms/op


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
# Warmup Iteration   1: 3.374 ±(99.9%) 0.080 ms/op
Iteration   1: 2.316 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.795 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   7.796 ms/op
                 createUser·p0.999:  32.338 ms/op
                 createUser·p0.9999: 35.258 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14136
  mean =      2.316 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11294 
    [ 2.500,  5.000) = 2600 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.795 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      7.796 ms/op
     p(99.9000) =     32.338 ms/op
     p(99.9900) =     35.258 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 2.959 ±(99.9%) 0.061 ms/op
Iteration   1: 1.785 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   3.047 ms/op
                 existUser·p0.999:  10.911 ms/op
                 existUser·p0.9999: 11.341 ms/op
                 existUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18050
  mean =      1.785 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 445 
    [ 1.250,  2.500) = 16777 
    [ 2.500,  3.750) = 714 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      3.047 ms/op
     p(99.9000) =     10.911 ms/op
     p(99.9900) =     11.341 ms/op
     p(99.9990) =     11.354 ms/op
     p(99.9999) =     11.354 ms/op
    p(100.0000) =     11.354 ms/op


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.121 ms/op
Iteration   1: 2.191 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.748 ms/op
                 getUser·p0.95:   2.990 ms/op
                 getUser·p0.99:   3.679 ms/op
                 getUser·p0.999:  10.355 ms/op
                 getUser·p0.9999: 10.469 ms/op
                 getUser·p1.00:   10.469 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14681
  mean =      2.191 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 21 
    [ 1.000,  2.000) = 5999 
    [ 2.000,  3.000) = 7953 
    [ 3.000,  4.000) = 595 
    [ 4.000,  5.000) = 35 
    [ 5.000,  6.000) = 11 
    [ 6.000,  7.000) = 34 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.679 ms/op
     p(99.9000) =     10.355 ms/op
     p(99.9900) =     10.469 ms/op
     p(99.9990) =     10.469 ms/op
     p(99.9999) =     10.469 ms/op
    p(100.0000) =     10.469 ms/op


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
# Warmup Iteration   1: 4.865 ±(99.9%) 0.160 ms/op
Iteration   1: 3.378 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.191 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.144 ms/op
                 listUser·p0.999:  23.560 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9468
  mean =      3.378 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 523 
    [ 2.500,  5.000) = 8790 
    [ 5.000,  7.500) = 84 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.644          ops/ms
ClientSimple.existUser                       thrpt         12.141          ops/ms
ClientSimple.getUser                         thrpt         14.887          ops/ms
ClientSimple.listUser                        thrpt          8.521          ops/ms
ClientSimple.createUser                       avgt          2.543           ms/op
ClientSimple.existUser                        avgt          2.079           ms/op
ClientSimple.getUser                          avgt          1.770           ms/op
ClientSimple.listUser                         avgt          3.000           ms/op
ClientSimple.createUser                     sample  14136   2.316 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.572           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.795           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.125           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.796           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.338           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.258           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.258           ms/op
ClientSimple.existUser                      sample  18050   1.785 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.625           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.690           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.047           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.911           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.341           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.354           ms/op
ClientSimple.getUser                        sample  14681   2.191 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.541           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.679           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.355           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.469           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.469           ms/op
ClientSimple.listUser                       sample   9468   3.378 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.200           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.191           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.014           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.144           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.560           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.593           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.593           ms/op

Benchmark result is saved to 1719016816547.json
