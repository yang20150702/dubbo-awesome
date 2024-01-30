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
# Warmup Iteration   1: 2.543 ops/ms
Iteration   1: 6.521 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.521 ops/ms


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
# Warmup Iteration   1: 6.424 ops/ms
Iteration   1: 13.569 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.569 ops/ms


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
# Warmup Iteration   1: 4.124 ops/ms
Iteration   1: 8.643 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.643 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.228 ops/ms
Iteration   1: 3.260 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.260 ops/ms


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
# Warmup Iteration   1: 5.013 ±(99.9%) 0.064 ms/op
Iteration   1: 3.144 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.144 ms/op


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
# Warmup Iteration   1: 3.000 ±(99.9%) 0.027 ms/op
Iteration   1: 1.846 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.846 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.045 ms/op
Iteration   1: 3.302 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.302 ms/op


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
# Warmup Iteration   1: 12.807 ±(99.9%) 0.223 ms/op
Iteration   1: 8.571 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.571 ms/op


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.128 ms/op
Iteration   1: 2.738 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.453 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  14.958 ms/op
                 createUser·p0.9999: 16.925 ms/op
                 createUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11667
  mean =      2.738 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 4106 
    [ 2.500,  3.750) = 7188 
    [ 3.750,  5.000) = 274 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.453 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =     14.958 ms/op
     p(99.9900) =     16.925 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 2.877 ±(99.9%) 0.060 ms/op
Iteration   1: 1.702 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   1.614 ms/op
                 existUser·p0.90:   2.095 ms/op
                 existUser·p0.95:   2.241 ms/op
                 existUser·p0.99:   2.930 ms/op
                 existUser·p0.999:  14.664 ms/op
                 existUser·p0.9999: 15.165 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18789
  mean =      1.702 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 978 
    [ 1.250,  2.500) = 17508 
    [ 2.500,  3.750) = 177 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.614 ms/op
     p(90.0000) =      2.095 ms/op
     p(95.0000) =      2.241 ms/op
     p(99.0000) =      2.930 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     15.165 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.101 ms/op
Iteration   1: 2.674 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.326 ms/op
                 getUser·p0.999:  5.430 ms/op
                 getUser·p0.9999: 7.697 ms/op
                 getUser·p1.00:   7.946 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12096
  mean =      2.674 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 64 
    [1.500, 2.000) = 848 
    [2.000, 2.500) = 4629 
    [2.500, 3.000) = 3576 
    [3.000, 3.500) = 1948 
    [3.500, 4.000) = 750 
    [4.000, 4.500) = 198 
    [4.500, 5.000) = 53 
    [5.000, 5.500) = 16 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.326 ms/op
     p(99.9000) =      5.430 ms/op
     p(99.9900) =      7.697 ms/op
     p(99.9990) =      7.946 ms/op
     p(99.9999) =      7.946 ms/op
    p(100.0000) =      7.946 ms/op


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
# Warmup Iteration   1: 13.652 ±(99.9%) 0.777 ms/op
Iteration   1: 8.602 ±(99.9%) 0.110 ms/op
                 listUser·p0.00:   3.514 ms/op
                 listUser·p0.50:   8.471 ms/op
                 listUser·p0.90:   11.069 ms/op
                 listUser·p0.95:   12.108 ms/op
                 listUser·p0.99:   14.631 ms/op
                 listUser·p0.999:  19.221 ms/op
                 listUser·p0.9999: 24.773 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3713
  mean =      8.602 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 76 
    [ 5.000,  7.500) = 1041 
    [ 7.500, 10.000) = 1816 
    [10.000, 12.500) = 636 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.514 ms/op
     p(50.0000) =      8.471 ms/op
     p(90.0000) =     11.069 ms/op
     p(95.0000) =     12.108 ms/op
     p(99.0000) =     14.631 ms/op
     p(99.9000) =     19.221 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.521          ops/ms
Client.existUser                       thrpt         13.569          ops/ms
Client.getUser                         thrpt          8.643          ops/ms
Client.listUser                        thrpt          3.260          ops/ms
Client.createUser                       avgt          3.144           ms/op
Client.existUser                        avgt          1.846           ms/op
Client.getUser                          avgt          3.302           ms/op
Client.listUser                         avgt          8.571           ms/op
Client.createUser                     sample  11667   2.738 ± 0.024   ms/op
Client.createUser:createUser·p0.00    sample          1.290           ms/op
Client.createUser:createUser·p0.50    sample          2.638           ms/op
Client.createUser:createUser·p0.90    sample          3.228           ms/op
Client.createUser:createUser·p0.95    sample          3.453           ms/op
Client.createUser:createUser·p0.99    sample          4.751           ms/op
Client.createUser:createUser·p0.999   sample         14.958           ms/op
Client.createUser:createUser·p0.9999  sample         16.925           ms/op
Client.createUser:createUser·p1.00    sample         16.941           ms/op
Client.existUser                      sample  18789   1.702 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.659           ms/op
Client.existUser:existUser·p0.50      sample          1.614           ms/op
Client.existUser:existUser·p0.90      sample          2.095           ms/op
Client.existUser:existUser·p0.95      sample          2.241           ms/op
Client.existUser:existUser·p0.99      sample          2.930           ms/op
Client.existUser:existUser·p0.999     sample         14.664           ms/op
Client.existUser:existUser·p0.9999    sample         15.165           ms/op
Client.existUser:existUser·p1.00      sample         15.237           ms/op
Client.getUser                        sample  12096   2.674 ± 0.017   ms/op
Client.getUser:getUser·p0.00          sample          0.837           ms/op
Client.getUser:getUser·p0.50          sample          2.548           ms/op
Client.getUser:getUser·p0.90          sample          3.445           ms/op
Client.getUser:getUser·p0.95          sample          3.690           ms/op
Client.getUser:getUser·p0.99          sample          4.326           ms/op
Client.getUser:getUser·p0.999         sample          5.430           ms/op
Client.getUser:getUser·p0.9999        sample          7.697           ms/op
Client.getUser:getUser·p1.00          sample          7.946           ms/op
Client.listUser                       sample   3713   8.602 ± 0.110   ms/op
Client.listUser:listUser·p0.00        sample          3.514           ms/op
Client.listUser:listUser·p0.50        sample          8.471           ms/op
Client.listUser:listUser·p0.90        sample         11.069           ms/op
Client.listUser:listUser·p0.95        sample         12.108           ms/op
Client.listUser:listUser·p0.99        sample         14.631           ms/op
Client.listUser:listUser·p0.999       sample         19.221           ms/op
Client.listUser:listUser·p0.9999      sample         24.773           ms/op
Client.listUser:listUser·p1.00        sample         24.773           ms/op
