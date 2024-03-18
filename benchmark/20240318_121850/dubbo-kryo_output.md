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
# Warmup Iteration   1: 0.593 ops/ms
Iteration   1: 5.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.177 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.451 ops/ms
Iteration   1: 12.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.625 ops/ms


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
# Warmup Iteration   1: 5.880 ops/ms
Iteration   1: 12.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.209 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.969 ops/ms
Iteration   1: 8.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.862 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ±(99.9%) 0.067 ms/op
Iteration   1: 2.055 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.055 ms/op


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
# Warmup Iteration   1: 3.549 ±(99.9%) 0.060 ms/op
Iteration   1: 1.982 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.982 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.077 ms/op
Iteration   1: 2.053 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.053 ms/op


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
# Warmup Iteration   1: 5.421 ±(99.9%) 0.120 ms/op
Iteration   1: 3.476 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.476 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.113 ms/op
Iteration   1: 2.377 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   2.277 ms/op
                 createUser·p0.90:   2.855 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  14.402 ms/op
                 createUser·p0.9999: 14.976 ms/op
                 createUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13484
  mean =      2.377 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 9439 
    [ 2.500,  3.750) = 3537 
    [ 3.750,  5.000) = 244 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     14.976 ms/op
     p(99.9990) =     15.204 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 3.613 ±(99.9%) 0.097 ms/op
Iteration   1: 1.854 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   1.731 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.452 ms/op
                 existUser·p0.999:  12.497 ms/op
                 existUser·p0.9999: 12.604 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17241
  mean =      1.854 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 15976 
    [ 2.500,  3.750) = 989 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.452 ms/op
     p(99.9000) =     12.497 ms/op
     p(99.9900) =     12.604 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.093 ms/op
Iteration   1: 2.008 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   1.890 ms/op
                 getUser·p0.90:   2.347 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  17.629 ms/op
                 getUser·p0.9999: 18.246 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15926
  mean =      2.008 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 14823 
    [ 2.500,  3.750) = 835 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     18.246 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.145 ms/op
Iteration   1: 3.630 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.829 ms/op
                 listUser·p0.9999: 12.927 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8839
  mean =      3.630 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 628 
    [ 2.500,  3.750) = 4719 
    [ 3.750,  5.000) = 3142 
    [ 5.000,  6.250) = 208 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.177          ops/ms
ClientSimple.existUser                       thrpt         12.625          ops/ms
ClientSimple.getUser                         thrpt         12.209          ops/ms
ClientSimple.listUser                        thrpt          8.862          ops/ms
ClientSimple.createUser                       avgt          2.055           ms/op
ClientSimple.existUser                        avgt          1.982           ms/op
ClientSimple.getUser                          avgt          2.053           ms/op
ClientSimple.listUser                         avgt          3.476           ms/op
ClientSimple.createUser                     sample  13484   2.377 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.674           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.277           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.195           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.792           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.402           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.976           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.204           ms/op
ClientSimple.existUser                      sample  17241   1.854 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.648           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.731           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.452           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.497           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.604           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.616           ms/op
ClientSimple.getUser                        sample  15926   2.008 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.865           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.890           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.347           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.694           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.629           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.246           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.285           ms/op
ClientSimple.listUser                       sample   8839   3.630 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.777           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.629           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.513           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.829           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.927           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.927           ms/op

Benchmark result is saved to 1710764067898.json
