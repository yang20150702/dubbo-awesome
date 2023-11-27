# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.401 ops/ms
Iteration   1: 5.723 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.723 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.829 ops/ms
Iteration   1: 13.776 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.776 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.563 ops/ms
Iteration   1: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.472 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.454 ops/ms
Iteration   1: 4.148 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.148 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.873 ±(99.9%) 0.063 ms/op
Iteration   1: 2.685 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.685 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ±(99.9%) 0.031 ms/op
Iteration   1: 1.845 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.845 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.386 ±(99.9%) 0.058 ms/op
Iteration   1: 2.860 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.166 ±(99.9%) 0.224 ms/op
Iteration   1: 8.376 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.376 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.453 ±(99.9%) 0.108 ms/op
Iteration   1: 2.877 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.388 ms/op
                 createUser·p0.999:  12.039 ms/op
                 createUser·p0.9999: 12.888 ms/op
                 createUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11225
  mean =      2.877 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 3663 
    [ 2.500,  3.750) = 6542 
    [ 3.750,  5.000) = 846 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.687 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      6.388 ms/op
     p(99.9000) =     12.039 ms/op
     p(99.9900) =     12.888 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.886 ±(99.9%) 0.067 ms/op
Iteration   1: 1.658 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   1.622 ms/op
                 existUser·p0.90:   2.019 ms/op
                 existUser·p0.95:   2.220 ms/op
                 existUser·p0.99:   3.095 ms/op
                 existUser·p0.999:  11.546 ms/op
                 existUser·p0.9999: 12.511 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19273
  mean =      1.658 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2150 
    [ 1.250,  2.500) = 16623 
    [ 2.500,  3.750) = 402 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      1.622 ms/op
     p(90.0000) =      2.019 ms/op
     p(95.0000) =      2.220 ms/op
     p(99.0000) =      3.095 ms/op
     p(99.9000) =     11.546 ms/op
     p(99.9900) =     12.511 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.814 ±(99.9%) 0.130 ms/op
Iteration   1: 3.304 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9690
  mean =      3.304 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1177 
    [ 2.500,  3.750) = 6689 
    [ 3.750,  5.000) = 1566 
    [ 5.000,  6.250) = 134 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.593 ±(99.9%) 0.414 ms/op
Iteration   1: 8.718 ±(99.9%) 0.126 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   8.311 ms/op
                 listUser·p0.90:   11.649 ms/op
                 listUser·p0.95:   12.716 ms/op
                 listUser·p0.99:   16.843 ms/op
                 listUser·p0.999:  21.176 ms/op
                 listUser·p0.9999: 23.167 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3676
  mean =      8.718 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 58 
    [ 5.000,  7.500) = 1060 
    [ 7.500, 10.000) = 1685 
    [10.000, 12.500) = 644 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.773 ms/op
     p(50.0000) =      8.311 ms/op
     p(90.0000) =     11.649 ms/op
     p(95.0000) =     12.716 ms/op
     p(99.0000) =     16.843 ms/op
     p(99.9000) =     21.176 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.723          ops/ms
Client.existUser                       thrpt         13.776          ops/ms
Client.getUser                         thrpt          9.472          ops/ms
Client.listUser                        thrpt          4.148          ops/ms
Client.createUser                       avgt          2.685           ms/op
Client.existUser                        avgt          1.845           ms/op
Client.getUser                          avgt          2.860           ms/op
Client.listUser                         avgt          8.376           ms/op
Client.createUser                     sample  11225   2.877 ± 0.026   ms/op
Client.createUser:createUser·p0.00    sample          0.867           ms/op
Client.createUser:createUser·p0.50    sample          2.687           ms/op
Client.createUser:createUser·p0.90    sample          3.711           ms/op
Client.createUser:createUser·p0.95    sample          4.018           ms/op
Client.createUser:createUser·p0.99    sample          6.388           ms/op
Client.createUser:createUser·p0.999   sample         12.039           ms/op
Client.createUser:createUser·p0.9999  sample         12.888           ms/op
Client.createUser:createUser·p1.00    sample         12.894           ms/op
Client.existUser                      sample  19273   1.658 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.711           ms/op
Client.existUser:existUser·p0.50      sample          1.622           ms/op
Client.existUser:existUser·p0.90      sample          2.019           ms/op
Client.existUser:existUser·p0.95      sample          2.220           ms/op
Client.existUser:existUser·p0.99      sample          3.095           ms/op
Client.existUser:existUser·p0.999     sample         11.546           ms/op
Client.existUser:existUser·p0.9999    sample         12.511           ms/op
Client.existUser:existUser·p1.00      sample         12.632           ms/op
Client.getUser                        sample   9690   3.304 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          0.965           ms/op
Client.getUser:getUser·p0.50          sample          3.183           ms/op
Client.getUser:getUser·p0.90          sample          4.084           ms/op
Client.getUser:getUser·p0.95          sample          4.514           ms/op
Client.getUser:getUser·p0.99          sample          7.348           ms/op
Client.getUser:getUser·p0.999         sample         16.843           ms/op
Client.getUser:getUser·p0.9999        sample         17.269           ms/op
Client.getUser:getUser·p1.00          sample         17.269           ms/op
Client.listUser                       sample   3676   8.718 ± 0.126   ms/op
Client.listUser:listUser·p0.00        sample          2.773           ms/op
Client.listUser:listUser·p0.50        sample          8.311           ms/op
Client.listUser:listUser·p0.90        sample         11.649           ms/op
Client.listUser:listUser·p0.95        sample         12.716           ms/op
Client.listUser:listUser·p0.99        sample         16.843           ms/op
Client.listUser:listUser·p0.999       sample         21.176           ms/op
Client.listUser:listUser·p0.9999      sample         23.167           ms/op
Client.listUser:listUser·p1.00        sample         23.167           ms/op
