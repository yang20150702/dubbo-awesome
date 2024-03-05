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
# Warmup Iteration   1: 1.954 ops/ms
Iteration   1: 5.809 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.809 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.915 ops/ms
Iteration   1: 11.515 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.515 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ops/ms
Iteration   1: 8.395 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.395 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.225 ops/ms
Iteration   1: 3.381 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.381 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.139 ±(99.9%) 0.096 ms/op
Iteration   1: 3.163 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.163 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ±(99.9%) 0.034 ms/op
Iteration   1: 1.784 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.784 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ±(99.9%) 0.053 ms/op
Iteration   1: 2.919 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.919 ms/op


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
# Warmup Iteration   1: 12.583 ±(99.9%) 0.397 ms/op
Iteration   1: 8.049 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.049 ms/op


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
# Warmup Iteration   1: 5.042 ±(99.9%) 0.136 ms/op
Iteration   1: 3.027 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.753 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   9.030 ms/op
                 createUser·p0.999:  14.720 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10541
  mean =      3.027 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2480 
    [ 2.500,  3.750) = 6710 
    [ 3.750,  5.000) = 963 
    [ 5.000,  6.250) = 177 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      9.030 ms/op
     p(99.9000) =     14.720 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.249 ±(99.9%) 0.071 ms/op
Iteration   1: 2.063 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.023 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.760 ms/op
                 existUser·p0.99:   3.945 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 8.613 ms/op
                 existUser·p1.00:   10.732 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15684
  mean =      2.063 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 206 
    [ 1.250,  2.500) = 13788 
    [ 2.500,  3.750) = 1509 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.760 ms/op
     p(99.0000) =      3.945 ms/op
     p(99.9000) =      6.275 ms/op
     p(99.9900) =      8.613 ms/op
     p(99.9990) =     10.732 ms/op
     p(99.9999) =     10.732 ms/op
    p(100.0000) =     10.732 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 5.554 ±(99.9%) 0.148 ms/op
Iteration   1: 3.076 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   2.863 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.419 ms/op
                 getUser·p0.999:  24.233 ms/op
                 getUser·p0.9999: 30.615 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10474
  mean =      3.076 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2445 
    [ 2.500,  5.000) = 7868 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.419 ms/op
     p(99.9000) =     24.233 ms/op
     p(99.9900) =     30.615 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.566 ±(99.9%) 0.421 ms/op
Iteration   1: 8.951 ±(99.9%) 0.138 ms/op
                 listUser·p0.00:   3.285 ms/op
                 listUser·p0.50:   8.471 ms/op
                 listUser·p0.90:   12.009 ms/op
                 listUser·p0.95:   13.910 ms/op
                 listUser·p0.99:   16.852 ms/op
                 listUser·p0.999:  23.574 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3570
  mean =      8.951 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 64 
    [ 5.000,  7.500) = 1015 
    [ 7.500, 10.000) = 1549 
    [10.000, 12.500) = 649 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.285 ms/op
     p(50.0000) =      8.471 ms/op
     p(90.0000) =     12.009 ms/op
     p(95.0000) =     13.910 ms/op
     p(99.0000) =     16.852 ms/op
     p(99.9000) =     23.574 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.809          ops/ms
Client.existUser                       thrpt         11.515          ops/ms
Client.getUser                         thrpt          8.395          ops/ms
Client.listUser                        thrpt          3.381          ops/ms
Client.createUser                       avgt          3.163           ms/op
Client.existUser                        avgt          1.784           ms/op
Client.getUser                          avgt          2.919           ms/op
Client.listUser                         avgt          8.049           ms/op
Client.createUser                     sample  10541   3.027 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.094           ms/op
Client.createUser:createUser·p0.50    sample          2.753           ms/op
Client.createUser:createUser·p0.90    sample          3.949           ms/op
Client.createUser:createUser·p0.95    sample          4.530           ms/op
Client.createUser:createUser·p0.99    sample          9.030           ms/op
Client.createUser:createUser·p0.999   sample         14.720           ms/op
Client.createUser:createUser·p0.9999  sample         17.629           ms/op
Client.createUser:createUser·p1.00    sample         17.629           ms/op
Client.existUser                      sample  15684   2.063 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.575           ms/op
Client.existUser:existUser·p0.50      sample          2.023           ms/op
Client.existUser:existUser·p0.90      sample          2.523           ms/op
Client.existUser:existUser·p0.95      sample          2.760           ms/op
Client.existUser:existUser·p0.99      sample          3.945           ms/op
Client.existUser:existUser·p0.999     sample          6.275           ms/op
Client.existUser:existUser·p0.9999    sample          8.613           ms/op
Client.existUser:existUser·p1.00      sample         10.732           ms/op
Client.getUser                        sample  10474   3.076 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample          0.758           ms/op
Client.getUser:getUser·p0.50          sample          2.863           ms/op
Client.getUser:getUser·p0.90          sample          3.838           ms/op
Client.getUser:getUser·p0.95          sample          4.162           ms/op
Client.getUser:getUser·p0.99          sample          5.419           ms/op
Client.getUser:getUser·p0.999         sample         24.233           ms/op
Client.getUser:getUser·p0.9999        sample         30.615           ms/op
Client.getUser:getUser·p1.00          sample         30.933           ms/op
Client.listUser                       sample   3570   8.951 ± 0.138   ms/op
Client.listUser:listUser·p0.00        sample          3.285           ms/op
Client.listUser:listUser·p0.50        sample          8.471           ms/op
Client.listUser:listUser·p0.90        sample         12.009           ms/op
Client.listUser:listUser·p0.95        sample         13.910           ms/op
Client.listUser:listUser·p0.99        sample         16.852           ms/op
Client.listUser:listUser·p0.999       sample         23.574           ms/op
Client.listUser:listUser·p0.9999      sample         24.445           ms/op
Client.listUser:listUser·p1.00        sample         24.445           ms/op
