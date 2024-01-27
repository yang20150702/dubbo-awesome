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
# Warmup Iteration   1: 2.445 ops/ms
Iteration   1: 5.320 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.320 ops/ms


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
# Warmup Iteration   1: 5.462 ops/ms
Iteration   1: 12.554 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.554 ops/ms


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
# Warmup Iteration   1: 3.928 ops/ms
Iteration   1: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.806 ops/ms


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
# Warmup Iteration   1: 2.133 ops/ms
Iteration   1: 3.139 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.139 ops/ms


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
# Warmup Iteration   1: 5.853 ±(99.9%) 0.071 ms/op
Iteration   1: 3.059 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.059 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.036 ms/op
Iteration   1: 2.063 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.063 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.042 ms/op
Iteration   1: 3.029 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.029 ms/op


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
# Warmup Iteration   1: 12.381 ±(99.9%) 0.200 ms/op
Iteration   1: 7.792 ±(99.9%) 0.105 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.792 ms/op


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.100 ms/op
Iteration   1: 2.900 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   2.802 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.739 ms/op
                 createUser·p0.999:  9.206 ms/op
                 createUser·p0.9999: 9.273 ms/op
                 createUser·p1.00:   9.273 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11127
  mean =      2.900 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 69 
    [ 1.500,  2.000) = 159 
    [ 2.000,  2.500) = 2674 
    [ 2.500,  3.000) = 4151 
    [ 3.000,  3.500) = 2548 
    [ 3.500,  4.000) = 1096 
    [ 4.000,  4.500) = 285 
    [ 4.500,  5.000) = 56 
    [ 5.000,  5.500) = 33 
    [ 5.500,  6.000) = 13 
    [ 6.000,  6.500) = 7 
    [ 6.500,  7.000) = 2 
    [ 7.000,  7.500) = 1 
    [ 7.500,  8.000) = 1 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.739 ms/op
     p(99.9000) =      9.206 ms/op
     p(99.9900) =      9.273 ms/op
     p(99.9990) =      9.273 ms/op
     p(99.9999) =      9.273 ms/op
    p(100.0000) =      9.273 ms/op


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
# Warmup Iteration   1: 2.960 ±(99.9%) 0.066 ms/op
Iteration   1: 1.834 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.375 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.867 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  6.560 ms/op
                 existUser·p0.9999: 7.405 ms/op
                 existUser·p1.00:   7.586 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17621
  mean =      1.834 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 269 
    [1.000, 1.500) = 5871 
    [1.500, 2.000) = 5703 
    [2.000, 2.500) = 3718 
    [2.500, 3.000) = 1486 
    [3.000, 3.500) = 346 
    [3.500, 4.000) = 74 
    [4.000, 4.500) = 29 
    [4.500, 5.000) = 16 
    [5.000, 5.500) = 15 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 43 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      6.560 ms/op
     p(99.9900) =      7.405 ms/op
     p(99.9990) =      7.586 ms/op
     p(99.9999) =      7.586 ms/op
    p(100.0000) =      7.586 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.104 ms/op
Iteration   1: 3.108 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.426 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 9.107 ms/op
                 getUser·p1.00:   9.110 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10255
  mean =      3.108 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 5 
    [ 1.000,  2.000) = 402 
    [ 2.000,  3.000) = 4382 
    [ 3.000,  4.000) = 4831 
    [ 4.000,  5.000) = 390 
    [ 5.000,  6.000) = 75 
    [ 6.000,  7.000) = 115 
    [ 7.000,  8.000) = 29 
    [ 8.000,  9.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.426 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =      9.107 ms/op
     p(99.9990) =      9.110 ms/op
     p(99.9999) =      9.110 ms/op
    p(100.0000) =      9.110 ms/op


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
# Warmup Iteration   1: 11.993 ±(99.9%) 0.355 ms/op
Iteration   1: 8.609 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   3.600 ms/op
                 listUser·p0.50:   8.241 ms/op
                 listUser·p0.90:   11.207 ms/op
                 listUser·p0.95:   12.789 ms/op
                 listUser·p0.99:   17.564 ms/op
                 listUser·p0.999:  18.945 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3707
  mean =      8.609 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 45 
    [ 5.000,  7.500) = 1307 
    [ 7.500, 10.000) = 1532 
    [10.000, 12.500) = 596 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.600 ms/op
     p(50.0000) =      8.241 ms/op
     p(90.0000) =     11.207 ms/op
     p(95.0000) =     12.789 ms/op
     p(99.0000) =     17.564 ms/op
     p(99.9000) =     18.945 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.320          ops/ms
Client.existUser                       thrpt         12.554          ops/ms
Client.getUser                         thrpt          7.806          ops/ms
Client.listUser                        thrpt          3.139          ops/ms
Client.createUser                       avgt          3.059           ms/op
Client.existUser                        avgt          2.063           ms/op
Client.getUser                          avgt          3.029           ms/op
Client.listUser                         avgt          7.792           ms/op
Client.createUser                     sample  11127   2.900 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          1.087           ms/op
Client.createUser:createUser·p0.50    sample          2.802           ms/op
Client.createUser:createUser·p0.90    sample          3.596           ms/op
Client.createUser:createUser·p0.95    sample          3.826           ms/op
Client.createUser:createUser·p0.99    sample          4.739           ms/op
Client.createUser:createUser·p0.999   sample          9.206           ms/op
Client.createUser:createUser·p0.9999  sample          9.273           ms/op
Client.createUser:createUser·p1.00    sample          9.273           ms/op
Client.existUser                      sample  17621   1.834 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.375           ms/op
Client.existUser:existUser·p0.50      sample          1.735           ms/op
Client.existUser:existUser·p0.90      sample          2.564           ms/op
Client.existUser:existUser·p0.95      sample          2.867           ms/op
Client.existUser:existUser·p0.99      sample          3.760           ms/op
Client.existUser:existUser·p0.999     sample          6.560           ms/op
Client.existUser:existUser·p0.9999    sample          7.405           ms/op
Client.existUser:existUser·p1.00      sample          7.586           ms/op
Client.getUser                        sample  10255   3.108 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.535           ms/op
Client.getUser:getUser·p0.50          sample          3.060           ms/op
Client.getUser:getUser·p0.90          sample          3.830           ms/op
Client.getUser:getUser·p0.95          sample          4.121           ms/op
Client.getUser:getUser·p0.99          sample          6.426           ms/op
Client.getUser:getUser·p0.999         sample          8.864           ms/op
Client.getUser:getUser·p0.9999        sample          9.107           ms/op
Client.getUser:getUser·p1.00          sample          9.110           ms/op
Client.listUser                       sample   3707   8.609 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          3.600           ms/op
Client.listUser:listUser·p0.50        sample          8.241           ms/op
Client.listUser:listUser·p0.90        sample         11.207           ms/op
Client.listUser:listUser·p0.95        sample         12.789           ms/op
Client.listUser:listUser·p0.99        sample         17.564           ms/op
Client.listUser:listUser·p0.999       sample         18.945           ms/op
Client.listUser:listUser·p0.9999      sample         20.742           ms/op
Client.listUser:listUser·p1.00        sample         20.742           ms/op
