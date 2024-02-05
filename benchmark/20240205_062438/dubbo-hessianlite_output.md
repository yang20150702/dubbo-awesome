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
# Warmup Iteration   1: 2.267 ops/ms
Iteration   1: 6.265 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.265 ops/ms


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
# Warmup Iteration   1: 6.086 ops/ms
Iteration   1: 13.913 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.913 ops/ms


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
# Warmup Iteration   1: 4.366 ops/ms
Iteration   1: 9.136 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.136 ops/ms


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
# Warmup Iteration   1: 2.373 ops/ms
Iteration   1: 3.827 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.827 ops/ms


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
# Warmup Iteration   1: 5.629 ±(99.9%) 0.077 ms/op
Iteration   1: 2.840 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.840 ms/op


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
# Warmup Iteration   1: 2.671 ±(99.9%) 0.028 ms/op
Iteration   1: 1.753 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.753 ms/op


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.081 ms/op
Iteration   1: 3.001 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.001 ms/op


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
# Warmup Iteration   1: 12.477 ±(99.9%) 0.260 ms/op
Iteration   1: 7.900 ±(99.9%) 0.073 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.900 ms/op


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
# Warmup Iteration   1: 4.749 ±(99.9%) 0.099 ms/op
Iteration   1: 3.080 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   2.879 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   9.488 ms/op
                 createUser·p0.999:  20.808 ms/op
                 createUser·p0.9999: 21.064 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10371
  mean =      3.080 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2784 
    [ 2.500,  5.000) = 7263 
    [ 5.000,  7.500) = 135 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      9.488 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     21.064 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 3.231 ±(99.9%) 0.069 ms/op
Iteration   1: 1.874 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.511 ms/op
                 existUser·p0.99:   4.269 ms/op
                 existUser·p0.999:  12.058 ms/op
                 existUser·p0.9999: 13.759 ms/op
                 existUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17046
  mean =      1.874 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1159 
    [ 1.250,  2.500) = 15013 
    [ 2.500,  3.750) = 644 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      4.269 ms/op
     p(99.9000) =     12.058 ms/op
     p(99.9900) =     13.759 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.116 ms/op
Iteration   1: 3.028 ±(99.9%) 0.050 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.884 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.271 ms/op
                 getUser·p0.999:  29.065 ms/op
                 getUser·p0.9999: 29.517 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10560
  mean =      3.028 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2434 
    [ 2.500,  5.000) = 7983 
    [ 5.000,  7.500) = 110 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.271 ms/op
     p(99.9000) =     29.065 ms/op
     p(99.9900) =     29.517 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 12.231 ±(99.9%) 0.381 ms/op
Iteration   1: 8.896 ±(99.9%) 0.167 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   8.241 ms/op
                 listUser·p0.90:   12.812 ms/op
                 listUser·p0.95:   14.885 ms/op
                 listUser·p0.99:   19.825 ms/op
                 listUser·p0.999:  23.005 ms/op
                 listUser·p0.9999: 37.159 ms/op
                 listUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3629
  mean =      8.896 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 105 
    [ 5.000,  7.500) = 1205 
    [ 7.500, 10.000) = 1378 
    [10.000, 12.500) = 511 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.052 ms/op
     p(50.0000) =      8.241 ms/op
     p(90.0000) =     12.812 ms/op
     p(95.0000) =     14.885 ms/op
     p(99.0000) =     19.825 ms/op
     p(99.9000) =     23.005 ms/op
     p(99.9900) =     37.159 ms/op
     p(99.9990) =     37.159 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.265          ops/ms
Client.existUser                       thrpt         13.913          ops/ms
Client.getUser                         thrpt          9.136          ops/ms
Client.listUser                        thrpt          3.827          ops/ms
Client.createUser                       avgt          2.840           ms/op
Client.existUser                        avgt          1.753           ms/op
Client.getUser                          avgt          3.001           ms/op
Client.listUser                         avgt          7.900           ms/op
Client.createUser                     sample  10371   3.080 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          1.335           ms/op
Client.createUser:createUser·p0.50    sample          2.879           ms/op
Client.createUser:createUser·p0.90    sample          3.777           ms/op
Client.createUser:createUser·p0.95    sample          4.260           ms/op
Client.createUser:createUser·p0.99    sample          9.488           ms/op
Client.createUser:createUser·p0.999   sample         20.808           ms/op
Client.createUser:createUser·p0.9999  sample         21.064           ms/op
Client.createUser:createUser·p1.00    sample         21.070           ms/op
Client.existUser                      sample  17046   1.874 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.526           ms/op
Client.existUser:existUser·p0.50      sample          1.835           ms/op
Client.existUser:existUser·p0.90      sample          2.294           ms/op
Client.existUser:existUser·p0.95      sample          2.511           ms/op
Client.existUser:existUser·p0.99      sample          4.269           ms/op
Client.existUser:existUser·p0.999     sample         12.058           ms/op
Client.existUser:existUser·p0.9999    sample         13.759           ms/op
Client.existUser:existUser·p1.00      sample         14.221           ms/op
Client.getUser                        sample  10560   3.028 ± 0.050   ms/op
Client.getUser:getUser·p0.00          sample          0.689           ms/op
Client.getUser:getUser·p0.50          sample          2.884           ms/op
Client.getUser:getUser·p0.90          sample          3.764           ms/op
Client.getUser:getUser·p0.95          sample          4.121           ms/op
Client.getUser:getUser·p0.99          sample          5.271           ms/op
Client.getUser:getUser·p0.999         sample         29.065           ms/op
Client.getUser:getUser·p0.9999        sample         29.517           ms/op
Client.getUser:getUser·p1.00          sample         29.524           ms/op
Client.listUser                       sample   3629   8.896 ± 0.167   ms/op
Client.listUser:listUser·p0.00        sample          2.052           ms/op
Client.listUser:listUser·p0.50        sample          8.241           ms/op
Client.listUser:listUser·p0.90        sample         12.812           ms/op
Client.listUser:listUser·p0.95        sample         14.885           ms/op
Client.listUser:listUser·p0.99        sample         19.825           ms/op
Client.listUser:listUser·p0.999       sample         23.005           ms/op
Client.listUser:listUser·p0.9999      sample         37.159           ms/op
Client.listUser:listUser·p1.00        sample         37.159           ms/op
