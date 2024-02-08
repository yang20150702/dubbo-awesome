# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.196 ops/ms
Iteration   1: 5.944 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.944 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.585 ops/ms
Iteration   1: 13.239 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.239 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ops/ms
Iteration   1: 8.083 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.083 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.107 ops/ms
Iteration   1: 3.481 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.481 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.139 ±(99.9%) 0.082 ms/op
Iteration   1: 3.279 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.279 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.667 ±(99.9%) 0.045 ms/op
Iteration   1: 1.965 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.965 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.738 ±(99.9%) 0.048 ms/op
Iteration   1: 3.249 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.249 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.583 ±(99.9%) 0.269 ms/op
Iteration   1: 9.341 ±(99.9%) 0.121 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ±(99.9%) 0.139 ms/op
Iteration   1: 2.988 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.748 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   7.061 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 18.636 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10728
  mean =      2.988 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 2951 
    [ 2.500,  3.750) = 6171 
    [ 3.750,  5.000) = 1344 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.061 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     18.636 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.292 ±(99.9%) 0.083 ms/op
Iteration   1: 1.904 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.088 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16799
  mean =      1.904 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1089 
    [ 1.250,  2.500) = 14450 
    [ 2.500,  3.750) = 1158 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.088 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     11.616 ms/op
     p(99.9990) =     11.616 ms/op
     p(99.9999) =     11.616 ms/op
    p(100.0000) =     11.616 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ±(99.9%) 0.112 ms/op
Iteration   1: 2.837 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  14.320 ms/op
                 getUser·p0.9999: 14.615 ms/op
                 getUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11280
  mean =      2.837 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 4147 
    [ 2.500,  3.750) = 6205 
    [ 3.750,  5.000) = 696 
    [ 5.000,  6.250) = 163 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     14.615 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.122 ±(99.9%) 0.399 ms/op
Iteration   1: 8.772 ±(99.9%) 0.126 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   8.454 ms/op
                 listUser·p0.90:   11.796 ms/op
                 listUser·p0.95:   12.895 ms/op
                 listUser·p0.99:   15.909 ms/op
                 listUser·p0.999:  20.077 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3638
  mean =      8.772 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 101 
    [ 5.000,  7.500) = 953 
    [ 7.500, 10.000) = 1700 
    [10.000, 12.500) = 652 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      8.454 ms/op
     p(90.0000) =     11.796 ms/op
     p(95.0000) =     12.895 ms/op
     p(99.0000) =     15.909 ms/op
     p(99.9000) =     20.077 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.944          ops/ms
Client.existUser                       thrpt         13.239          ops/ms
Client.getUser                         thrpt          8.083          ops/ms
Client.listUser                        thrpt          3.481          ops/ms
Client.createUser                       avgt          3.279           ms/op
Client.existUser                        avgt          1.965           ms/op
Client.getUser                          avgt          3.249           ms/op
Client.listUser                         avgt          9.341           ms/op
Client.createUser                     sample  10728   2.988 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          0.977           ms/op
Client.createUser:createUser·p0.50    sample          2.748           ms/op
Client.createUser:createUser·p0.90    sample          4.043           ms/op
Client.createUser:createUser·p0.95    sample          4.366           ms/op
Client.createUser:createUser·p0.99    sample          7.061           ms/op
Client.createUser:createUser·p0.999   sample         17.433           ms/op
Client.createUser:createUser·p0.9999  sample         18.636           ms/op
Client.createUser:createUser·p1.00    sample         18.711           ms/op
Client.existUser                      sample  16799   1.904 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.647           ms/op
Client.existUser:existUser·p0.50      sample          1.870           ms/op
Client.existUser:existUser·p0.90      sample          2.433           ms/op
Client.existUser:existUser·p0.95      sample          2.585           ms/op
Client.existUser:existUser·p0.99      sample          3.088           ms/op
Client.existUser:existUser·p0.999     sample         11.190           ms/op
Client.existUser:existUser·p0.9999    sample         11.616           ms/op
Client.existUser:existUser·p1.00      sample         11.616           ms/op
Client.getUser                        sample  11280   2.837 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          0.992           ms/op
Client.getUser:getUser·p0.50          sample          2.634           ms/op
Client.getUser:getUser·p0.90          sample          3.654           ms/op
Client.getUser:getUser·p0.95          sample          3.969           ms/op
Client.getUser:getUser·p0.99          sample          5.874           ms/op
Client.getUser:getUser·p0.999         sample         14.320           ms/op
Client.getUser:getUser·p0.9999        sample         14.615           ms/op
Client.getUser:getUser·p1.00          sample         14.615           ms/op
Client.listUser                       sample   3638   8.772 ± 0.126   ms/op
Client.listUser:listUser·p0.00        sample          2.075           ms/op
Client.listUser:listUser·p0.50        sample          8.454           ms/op
Client.listUser:listUser·p0.90        sample         11.796           ms/op
Client.listUser:listUser·p0.95        sample         12.895           ms/op
Client.listUser:listUser·p0.99        sample         15.909           ms/op
Client.listUser:listUser·p0.999       sample         20.077           ms/op
Client.listUser:listUser·p0.9999      sample         21.496           ms/op
Client.listUser:listUser·p1.00        sample         21.496           ms/op
