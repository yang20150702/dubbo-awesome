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
# Warmup Iteration   1: 2.435 ops/ms
Iteration   1: 6.277 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.277 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.505 ops/ms
Iteration   1: 12.621 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.621 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.644 ops/ms
Iteration   1: 8.776 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.776 ops/ms


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
# Warmup Iteration   1: 2.194 ops/ms
Iteration   1: 4.134 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.134 ops/ms


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.076 ms/op
Iteration   1: 2.800 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.800 ms/op


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
# Warmup Iteration   1: 2.663 ±(99.9%) 0.027 ms/op
Iteration   1: 1.788 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.788 ms/op


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.054 ms/op
Iteration   1: 2.945 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.945 ms/op


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
# Warmup Iteration   1: 11.937 ±(99.9%) 0.235 ms/op
Iteration   1: 7.776 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.776 ms/op


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
# Warmup Iteration   1: 5.084 ±(99.9%) 0.121 ms/op
Iteration   1: 3.131 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.800 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   7.388 ms/op
                 createUser·p0.999:  9.355 ms/op
                 createUser·p0.9999: 9.601 ms/op
                 createUser·p1.00:   9.601 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10212
  mean =      3.131 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 23 
    [ 1.500,  2.000) = 66 
    [ 2.000,  2.500) = 1097 
    [ 2.500,  3.000) = 4211 
    [ 3.000,  3.500) = 3070 
    [ 3.500,  4.000) = 1004 
    [ 4.000,  4.500) = 380 
    [ 4.500,  5.000) = 108 
    [ 5.000,  5.500) = 15 
    [ 5.500,  6.000) = 18 
    [ 6.000,  6.500) = 44 
    [ 6.500,  7.000) = 45 
    [ 7.000,  7.500) = 40 
    [ 7.500,  8.000) = 24 
    [ 8.000,  8.500) = 32 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.800 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.388 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =      9.601 ms/op
     p(99.9990) =      9.601 ms/op
     p(99.9999) =      9.601 ms/op
    p(100.0000) =      9.601 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.084 ms/op
Iteration   1: 2.058 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   2.050 ms/op
                 existUser·p0.90:   2.605 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.107 ms/op
                 existUser·p0.9999: 6.942 ms/op
                 existUser·p1.00:   6.947 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15554
  mean =      2.058 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 85 
    [1.000, 1.500) = 1968 
    [1.500, 2.000) = 4968 
    [2.000, 2.500) = 6177 
    [2.500, 3.000) = 2036 
    [3.000, 3.500) = 169 
    [3.500, 4.000) = 63 
    [4.000, 4.500) = 25 
    [4.500, 5.000) = 20 
    [5.000, 5.500) = 15 
    [5.500, 6.000) = 11 
    [6.000, 6.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =      6.107 ms/op
     p(99.9900) =      6.942 ms/op
     p(99.9990) =      6.947 ms/op
     p(99.9999) =      6.947 ms/op
    p(100.0000) =      6.947 ms/op


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.094 ms/op
Iteration   1: 2.744 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   2.675 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  18.253 ms/op
                 getUser·p0.9999: 19.124 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11947
  mean =      2.744 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 4837 
    [ 2.500,  3.750) = 6589 
    [ 3.750,  5.000) = 404 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =     18.253 ms/op
     p(99.9900) =     19.124 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 11.874 ±(99.9%) 0.343 ms/op
Iteration   1: 7.999 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   7.528 ms/op
                 listUser·p0.90:   10.764 ms/op
                 listUser·p0.95:   12.304 ms/op
                 listUser·p0.99:   17.407 ms/op
                 listUser·p0.999:  22.586 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4038
  mean =      7.999 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 146 
    [ 5.000,  7.500) = 1838 
    [ 7.500, 10.000) = 1503 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.105 ms/op
     p(50.0000) =      7.528 ms/op
     p(90.0000) =     10.764 ms/op
     p(95.0000) =     12.304 ms/op
     p(99.0000) =     17.407 ms/op
     p(99.9000) =     22.586 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.277          ops/ms
Client.existUser                       thrpt         12.621          ops/ms
Client.getUser                         thrpt          8.776          ops/ms
Client.listUser                        thrpt          4.134          ops/ms
Client.createUser                       avgt          2.800           ms/op
Client.existUser                        avgt          1.788           ms/op
Client.getUser                          avgt          2.945           ms/op
Client.listUser                         avgt          7.776           ms/op
Client.createUser                     sample  10212   3.131 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.147           ms/op
Client.createUser:createUser·p0.50    sample          2.970           ms/op
Client.createUser:createUser·p0.90    sample          3.800           ms/op
Client.createUser:createUser·p0.95    sample          4.276           ms/op
Client.createUser:createUser·p0.99    sample          7.388           ms/op
Client.createUser:createUser·p0.999   sample          9.355           ms/op
Client.createUser:createUser·p0.9999  sample          9.601           ms/op
Client.createUser:createUser·p1.00    sample          9.601           ms/op
Client.existUser                      sample  15554   2.058 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.565           ms/op
Client.existUser:existUser·p0.50      sample          2.050           ms/op
Client.existUser:existUser·p0.90      sample          2.605           ms/op
Client.existUser:existUser·p0.95      sample          2.740           ms/op
Client.existUser:existUser·p0.99      sample          3.482           ms/op
Client.existUser:existUser·p0.999     sample          6.107           ms/op
Client.existUser:existUser·p0.9999    sample          6.942           ms/op
Client.existUser:existUser·p1.00      sample          6.947           ms/op
Client.getUser                        sample  11947   2.744 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.610           ms/op
Client.getUser:getUser·p0.50          sample          2.675           ms/op
Client.getUser:getUser·p0.90          sample          3.441           ms/op
Client.getUser:getUser·p0.95          sample          3.662           ms/op
Client.getUser:getUser·p0.99          sample          4.383           ms/op
Client.getUser:getUser·p0.999         sample         18.253           ms/op
Client.getUser:getUser·p0.9999        sample         19.124           ms/op
Client.getUser:getUser·p1.00          sample         19.137           ms/op
Client.listUser                       sample   4038   7.999 ± 0.125   ms/op
Client.listUser:listUser·p0.00        sample          2.105           ms/op
Client.listUser:listUser·p0.50        sample          7.528           ms/op
Client.listUser:listUser·p0.90        sample         10.764           ms/op
Client.listUser:listUser·p0.95        sample         12.304           ms/op
Client.listUser:listUser·p0.99        sample         17.407           ms/op
Client.listUser:listUser·p0.999       sample         22.586           ms/op
Client.listUser:listUser·p0.9999      sample         25.166           ms/op
Client.listUser:listUser·p1.00        sample         25.166           ms/op
