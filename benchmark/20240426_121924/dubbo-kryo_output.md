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
# Warmup Iteration   1: 1.854 ops/ms
Iteration   1: 6.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.930 ops/ms


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
# Warmup Iteration   1: 4.734 ops/ms
Iteration   1: 11.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.707 ops/ms


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
# Warmup Iteration   1: 5.170 ops/ms
Iteration   1: 11.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.075 ops/ms


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
# Warmup Iteration   1: 4.624 ops/ms
Iteration   1: 7.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.644 ops/ms


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.065 ms/op
Iteration   1: 2.011 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.011 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.053 ms/op
Iteration   1: 1.823 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.823 ms/op


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
# Warmup Iteration   1: 3.501 ±(99.9%) 0.053 ms/op
Iteration   1: 1.862 ±(99.9%) 0.004 ms/op


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
# Warmup Iteration   1: 4.365 ±(99.9%) 0.090 ms/op
Iteration   1: 3.133 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.133 ms/op


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
# Warmup Iteration   1: 3.412 ±(99.9%) 0.082 ms/op
Iteration   1: 2.353 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.228 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   2.937 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  37.093 ms/op
                 createUser·p0.9999: 38.535 ms/op
                 createUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13584
  mean =      2.353 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10860 
    [ 2.500,  5.000) = 2599 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.228 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      4.973 ms/op
     p(99.9000) =     37.093 ms/op
     p(99.9900) =     38.535 ms/op
     p(99.9990) =     38.535 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.075 ms/op
Iteration   1: 1.918 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   1.817 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   4.769 ms/op
                 existUser·p0.999:  22.741 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16680
  mean =      1.918 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15938 
    [ 2.500,  5.000) = 595 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      4.769 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.078 ms/op
Iteration   1: 2.016 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.421 ms/op
                 getUser·p0.95:   2.761 ms/op
                 getUser·p0.99:   3.436 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 12.445 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16016
  mean =      2.016 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 14687 
    [ 2.500,  3.750) = 1188 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      3.436 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     12.445 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 5.125 ±(99.9%) 0.151 ms/op
Iteration   1: 3.396 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9445
  mean =      3.396 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1555 
    [ 2.500,  3.750) = 4810 
    [ 3.750,  5.000) = 2691 
    [ 5.000,  6.250) = 246 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.930          ops/ms
ClientSimple.existUser                       thrpt         11.707          ops/ms
ClientSimple.getUser                         thrpt         11.075          ops/ms
ClientSimple.listUser                        thrpt          7.644          ops/ms
ClientSimple.createUser                       avgt          2.011           ms/op
ClientSimple.existUser                        avgt          1.823           ms/op
ClientSimple.getUser                          avgt          1.862           ms/op
ClientSimple.listUser                         avgt          3.133           ms/op
ClientSimple.createUser                     sample  13584   2.353 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.662           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.228           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.973           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.093           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.535           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.535           ms/op
ClientSimple.existUser                      sample  16680   1.918 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.497           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.817           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.769           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.741           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.265           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.331           ms/op
ClientSimple.getUser                        sample  16016   2.016 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.006           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.436           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.091           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.445           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.485           ms/op
ClientSimple.listUser                       sample   9445   3.396 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.198           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.603           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.940           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.825           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.825           ms/op

Benchmark result is saved to 1714133723550.json
