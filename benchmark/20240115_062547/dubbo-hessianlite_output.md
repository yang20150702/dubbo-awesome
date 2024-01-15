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
# Warmup Iteration   1: 2.455 ops/ms
Iteration   1: 5.768 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.768 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.125 ops/ms
Iteration   1: 13.673 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.673 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.366 ops/ms
Iteration   1: 8.950 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.950 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.208 ops/ms
Iteration   1: 3.530 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.530 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.508 ±(99.9%) 0.096 ms/op
Iteration   1: 3.252 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.252 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.322 ±(99.9%) 0.033 ms/op
Iteration   1: 1.821 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.821 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.907 ±(99.9%) 0.065 ms/op
Iteration   1: 3.096 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.096 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.596 ±(99.9%) 0.193 ms/op
Iteration   1: 9.610 ±(99.9%) 0.142 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.610 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.783 ±(99.9%) 0.107 ms/op
Iteration   1: 3.035 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   2.765 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.376 ms/op
                 createUser·p0.999:  10.732 ms/op
                 createUser·p0.9999: 11.912 ms/op
                 createUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10533
  mean =      3.035 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2850 
    [ 2.500,  3.750) = 6004 
    [ 3.750,  5.000) = 1378 
    [ 5.000,  6.250) = 193 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.376 ms/op
     p(99.9000) =     10.732 ms/op
     p(99.9900) =     11.912 ms/op
     p(99.9990) =     11.977 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.178 ±(99.9%) 0.076 ms/op
Iteration   1: 1.925 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   1.776 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.716 ms/op
                 existUser·p0.99:   3.847 ms/op
                 existUser·p0.999:  14.041 ms/op
                 existUser·p0.9999: 14.692 ms/op
                 existUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16584
  mean =      1.925 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 14960 
    [ 2.500,  3.750) = 1379 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      3.847 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     14.692 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 5.232 ±(99.9%) 0.106 ms/op
Iteration   1: 3.189 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.785 ms/op
                 getUser·p0.999:  8.814 ms/op
                 getUser·p0.9999: 8.929 ms/op
                 getUser·p1.00:   8.929 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10020
  mean =      3.189 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 108 
    [2.000, 2.500) = 1821 
    [2.500, 3.000) = 2785 
    [3.000, 3.500) = 2253 
    [3.500, 4.000) = 1663 
    [4.000, 4.500) = 902 
    [4.500, 5.000) = 227 
    [5.000, 5.500) = 111 
    [5.500, 6.000) = 48 
    [6.000, 6.500) = 52 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.785 ms/op
     p(99.9000) =      8.814 ms/op
     p(99.9900) =      8.929 ms/op
     p(99.9990) =      8.929 ms/op
     p(99.9999) =      8.929 ms/op
    p(100.0000) =      8.929 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.076 ±(99.9%) 0.429 ms/op
Iteration   1: 8.264 ±(99.9%) 0.104 ms/op
                 listUser·p0.00:   3.375 ms/op
                 listUser·p0.50:   7.963 ms/op
                 listUser·p0.90:   10.289 ms/op
                 listUser·p0.95:   11.304 ms/op
                 listUser·p0.99:   15.293 ms/op
                 listUser·p0.999:  22.620 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3880
  mean =      8.264 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 33 
    [ 5.000,  7.500) = 1353 
    [ 7.500, 10.000) = 1995 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.375 ms/op
     p(50.0000) =      7.963 ms/op
     p(90.0000) =     10.289 ms/op
     p(95.0000) =     11.304 ms/op
     p(99.0000) =     15.293 ms/op
     p(99.9000) =     22.620 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.768          ops/ms
Client.existUser                       thrpt         13.673          ops/ms
Client.getUser                         thrpt          8.950          ops/ms
Client.listUser                        thrpt          3.530          ops/ms
Client.createUser                       avgt          3.252           ms/op
Client.existUser                        avgt          1.821           ms/op
Client.getUser                          avgt          3.096           ms/op
Client.listUser                         avgt          9.610           ms/op
Client.createUser                     sample  10533   3.035 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.497           ms/op
Client.createUser:createUser·p0.50    sample          2.765           ms/op
Client.createUser:createUser·p0.90    sample          4.022           ms/op
Client.createUser:createUser·p0.95    sample          4.538           ms/op
Client.createUser:createUser·p0.99    sample          6.376           ms/op
Client.createUser:createUser·p0.999   sample         10.732           ms/op
Client.createUser:createUser·p0.9999  sample         11.912           ms/op
Client.createUser:createUser·p1.00    sample         11.977           ms/op
Client.existUser                      sample  16584   1.925 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.869           ms/op
Client.existUser:existUser·p0.50      sample          1.776           ms/op
Client.existUser:existUser·p0.90      sample          2.478           ms/op
Client.existUser:existUser·p0.95      sample          2.716           ms/op
Client.existUser:existUser·p0.99      sample          3.847           ms/op
Client.existUser:existUser·p0.999     sample         14.041           ms/op
Client.existUser:existUser·p0.9999    sample         14.692           ms/op
Client.existUser:existUser·p1.00      sample         14.746           ms/op
Client.getUser                        sample  10020   3.189 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.814           ms/op
Client.getUser:getUser·p0.50          sample          3.064           ms/op
Client.getUser:getUser·p0.90          sample          4.194           ms/op
Client.getUser:getUser·p0.95          sample          4.465           ms/op
Client.getUser:getUser·p0.99          sample          5.785           ms/op
Client.getUser:getUser·p0.999         sample          8.814           ms/op
Client.getUser:getUser·p0.9999        sample          8.929           ms/op
Client.getUser:getUser·p1.00          sample          8.929           ms/op
Client.listUser                       sample   3880   8.264 ± 0.104   ms/op
Client.listUser:listUser·p0.00        sample          3.375           ms/op
Client.listUser:listUser·p0.50        sample          7.963           ms/op
Client.listUser:listUser·p0.90        sample         10.289           ms/op
Client.listUser:listUser·p0.95        sample         11.304           ms/op
Client.listUser:listUser·p0.99        sample         15.293           ms/op
Client.listUser:listUser·p0.999       sample         22.620           ms/op
Client.listUser:listUser·p0.9999      sample         24.510           ms/op
Client.listUser:listUser·p1.00        sample         24.510           ms/op
