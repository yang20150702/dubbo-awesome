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
# Warmup Iteration   1: 2.274 ops/ms
Iteration   1: 5.903 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.903 ops/ms


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
# Warmup Iteration   1: 7.247 ops/ms
Iteration   1: 13.500 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.500 ops/ms


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
# Warmup Iteration   1: 4.287 ops/ms
Iteration   1: 9.210 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.210 ops/ms


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
# Warmup Iteration   1: 2.084 ops/ms
Iteration   1: 4.298 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.298 ops/ms


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
# Warmup Iteration   1: 5.968 ±(99.9%) 0.103 ms/op
Iteration   1: 3.175 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.175 ms/op


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
# Warmup Iteration   1: 3.312 ±(99.9%) 0.043 ms/op
Iteration   1: 1.984 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.984 ms/op


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.063 ms/op
Iteration   1: 3.128 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.128 ms/op


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
# Warmup Iteration   1: 12.377 ±(99.9%) 0.245 ms/op
Iteration   1: 9.130 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.130 ms/op


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
# Warmup Iteration   1: 5.245 ±(99.9%) 0.125 ms/op
Iteration   1: 2.875 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  14.483 ms/op
                 createUser·p0.9999: 15.071 ms/op
                 createUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11114
  mean =      2.875 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2856 
    [ 2.500,  3.750) = 7489 
    [ 3.750,  5.000) = 418 
    [ 5.000,  6.250) = 108 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     15.071 ms/op
     p(99.9990) =     15.122 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.077 ms/op
Iteration   1: 1.954 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.540 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  19.890 ms/op
                 existUser·p0.9999: 20.032 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16649
  mean =      1.954 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14827 
    [ 2.500,  5.000) = 1789 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.363 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     20.032 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.098 ms/op
Iteration   1: 2.894 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   2.851 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.957 ms/op
                 getUser·p0.999:  6.046 ms/op
                 getUser·p0.9999: 8.733 ms/op
                 getUser·p1.00:   8.929 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11094
  mean =      2.894 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 43 
    [1.500, 2.000) = 434 
    [2.000, 2.500) = 2891 
    [2.500, 3.000) = 3263 
    [3.000, 3.500) = 2760 
    [3.500, 4.000) = 1188 
    [4.000, 4.500) = 318 
    [4.500, 5.000) = 97 
    [5.000, 5.500) = 66 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.957 ms/op
     p(99.9000) =      6.046 ms/op
     p(99.9900) =      8.733 ms/op
     p(99.9990) =      8.929 ms/op
     p(99.9999) =      8.929 ms/op
    p(100.0000) =      8.929 ms/op


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
# Warmup Iteration   1: 12.850 ±(99.9%) 0.432 ms/op
Iteration   1: 8.240 ±(99.9%) 0.124 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   7.807 ms/op
                 listUser·p0.90:   10.994 ms/op
                 listUser·p0.95:   12.190 ms/op
                 listUser·p0.99:   17.531 ms/op
                 listUser·p0.999:  22.099 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3952
  mean =      8.240 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 89 
    [ 5.000,  7.500) = 1590 
    [ 7.500, 10.000) = 1539 
    [10.000, 12.500) = 568 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.645 ms/op
     p(50.0000) =      7.807 ms/op
     p(90.0000) =     10.994 ms/op
     p(95.0000) =     12.190 ms/op
     p(99.0000) =     17.531 ms/op
     p(99.9000) =     22.099 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.903          ops/ms
Client.existUser                       thrpt         13.500          ops/ms
Client.getUser                         thrpt          9.210          ops/ms
Client.listUser                        thrpt          4.298          ops/ms
Client.createUser                       avgt          3.175           ms/op
Client.existUser                        avgt          1.984           ms/op
Client.getUser                          avgt          3.128           ms/op
Client.listUser                         avgt          9.130           ms/op
Client.createUser                     sample  11114   2.875 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.247           ms/op
Client.createUser:createUser·p0.50    sample          2.634           ms/op
Client.createUser:createUser·p0.90    sample          3.461           ms/op
Client.createUser:createUser·p0.95    sample          4.141           ms/op
Client.createUser:createUser·p0.99    sample          7.758           ms/op
Client.createUser:createUser·p0.999   sample         14.483           ms/op
Client.createUser:createUser·p0.9999  sample         15.071           ms/op
Client.createUser:createUser·p1.00    sample         15.122           ms/op
Client.existUser                      sample  16649   1.954 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.680           ms/op
Client.existUser:existUser·p0.50      sample          1.788           ms/op
Client.existUser:existUser·p0.90      sample          2.540           ms/op
Client.existUser:existUser·p0.95      sample          2.777           ms/op
Client.existUser:existUser·p0.99      sample          3.363           ms/op
Client.existUser:existUser·p0.999     sample         19.890           ms/op
Client.existUser:existUser·p0.9999    sample         20.032           ms/op
Client.existUser:existUser·p1.00      sample         20.054           ms/op
Client.getUser                        sample  11094   2.894 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.731           ms/op
Client.getUser:getUser·p0.50          sample          2.851           ms/op
Client.getUser:getUser·p0.90          sample          3.690           ms/op
Client.getUser:getUser·p0.95          sample          3.961           ms/op
Client.getUser:getUser·p0.99          sample          4.957           ms/op
Client.getUser:getUser·p0.999         sample          6.046           ms/op
Client.getUser:getUser·p0.9999        sample          8.733           ms/op
Client.getUser:getUser·p1.00          sample          8.929           ms/op
Client.listUser                       sample   3952   8.240 ± 0.124   ms/op
Client.listUser:listUser·p0.00        sample          1.645           ms/op
Client.listUser:listUser·p0.50        sample          7.807           ms/op
Client.listUser:listUser·p0.90        sample         10.994           ms/op
Client.listUser:listUser·p0.95        sample         12.190           ms/op
Client.listUser:listUser·p0.99        sample         17.531           ms/op
Client.listUser:listUser·p0.999       sample         22.099           ms/op
Client.listUser:listUser·p0.9999      sample         22.708           ms/op
Client.listUser:listUser·p1.00        sample         22.708           ms/op
