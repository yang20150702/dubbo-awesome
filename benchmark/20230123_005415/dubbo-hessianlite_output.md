# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.160 ops/ms
Iteration   1: 2.236 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.236 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.734 ops/ms
Iteration   1: 5.827 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.827 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.074 ops/ms
Iteration   1: 4.596 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.596 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.895 ops/ms
Iteration   1: 1.285 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.285 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 18.063 ±(99.9%) 0.227 ms/op
Iteration   1: 8.371 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.371 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.773 ±(99.9%) 0.088 ms/op
Iteration   1: 4.726 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.609 ±(99.9%) 0.136 ms/op
Iteration   1: 5.417 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.417 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.525 ±(99.9%) 0.378 ms/op
Iteration   1: 15.476 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.476 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.105 ±(99.9%) 0.554 ms/op
Iteration   1: 7.853 ±(99.9%) 0.122 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   7.930 ms/op
                 createUser·p0.90:   8.815 ms/op
                 createUser·p0.95:   9.110 ms/op
                 createUser·p0.99:   20.685 ms/op
                 createUser·p0.999:  21.032 ms/op
                 createUser·p0.9999: 24.314 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4072
  mean =      7.853 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 149 
    [ 2.500,  5.000) = 154 
    [ 5.000,  7.500) = 726 
    [ 7.500, 10.000) = 2876 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      7.930 ms/op
     p(90.0000) =      8.815 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     20.685 ms/op
     p(99.9000) =     21.032 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.425 ±(99.9%) 0.194 ms/op
Iteration   1: 4.186 ±(99.9%) 0.085 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   6.406 ms/op
                 existUser·p0.95:   10.420 ms/op
                 existUser·p0.99:   13.660 ms/op
                 existUser·p0.999:  16.576 ms/op
                 existUser·p0.9999: 17.105 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7646
  mean =      4.186 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 434 
    [ 2.500,  3.750) = 4468 
    [ 3.750,  5.000) = 1371 
    [ 5.000,  6.250) = 572 
    [ 6.250,  7.500) = 200 
    [ 7.500,  8.750) = 129 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 191 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =     10.420 ms/op
     p(99.0000) =     13.660 ms/op
     p(99.9000) =     16.576 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.526 ±(99.9%) 0.305 ms/op
Iteration   1: 3.739 ±(99.9%) 0.067 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   5.541 ms/op
                 getUser·p0.95:   6.791 ms/op
                 getUser·p0.99:   10.062 ms/op
                 getUser·p0.999:  20.624 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8595
  mean =      3.739 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1665 
    [ 2.500,  5.000) = 5659 
    [ 5.000,  7.500) = 1004 
    [ 7.500, 10.000) = 180 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      5.541 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =     10.062 ms/op
     p(99.9000) =     20.624 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.535 ±(99.9%) 0.837 ms/op
Iteration   1: 16.979 ±(99.9%) 0.179 ms/op
                 listUser·p0.00:   5.980 ms/op
                 listUser·p0.50:   16.843 ms/op
                 listUser·p0.90:   19.117 ms/op
                 listUser·p0.95:   19.694 ms/op
                 listUser·p0.99:   26.115 ms/op
                 listUser·p0.999:  29.884 ms/op
                 listUser·p0.9999: 30.900 ms/op
                 listUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1885
  mean =     16.979 ±(99.9%) 0.179 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 1238 
    [17.500, 20.000) = 432 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.980 ms/op
     p(50.0000) =     16.843 ms/op
     p(90.0000) =     19.117 ms/op
     p(95.0000) =     19.694 ms/op
     p(99.0000) =     26.115 ms/op
     p(99.9000) =     29.884 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.236          ops/ms
Client.existUser                       thrpt         5.827          ops/ms
Client.getUser                         thrpt         4.596          ops/ms
Client.listUser                        thrpt         1.285          ops/ms
Client.createUser                       avgt         8.371           ms/op
Client.existUser                        avgt         4.726           ms/op
Client.getUser                          avgt         5.417           ms/op
Client.listUser                         avgt        15.476           ms/op
Client.createUser                     sample  4072   7.853 ± 0.122   ms/op
Client.createUser:createUser·p0.00    sample         1.341           ms/op
Client.createUser:createUser·p0.50    sample         7.930           ms/op
Client.createUser:createUser·p0.90    sample         8.815           ms/op
Client.createUser:createUser·p0.95    sample         9.110           ms/op
Client.createUser:createUser·p0.99    sample        20.685           ms/op
Client.createUser:createUser·p0.999   sample        21.032           ms/op
Client.createUser:createUser·p0.9999  sample        24.314           ms/op
Client.createUser:createUser·p1.00    sample        24.314           ms/op
Client.existUser                      sample  7646   4.186 ± 0.085   ms/op
Client.existUser:existUser·p0.00      sample         0.923           ms/op
Client.existUser:existUser·p0.50      sample         3.322           ms/op
Client.existUser:existUser·p0.90      sample         6.406           ms/op
Client.existUser:existUser·p0.95      sample        10.420           ms/op
Client.existUser:existUser·p0.99      sample        13.660           ms/op
Client.existUser:existUser·p0.999     sample        16.576           ms/op
Client.existUser:existUser·p0.9999    sample        17.105           ms/op
Client.existUser:existUser·p1.00      sample        17.105           ms/op
Client.getUser                        sample  8595   3.739 ± 0.067   ms/op
Client.getUser:getUser·p0.00          sample         0.715           ms/op
Client.getUser:getUser·p0.50          sample         3.162           ms/op
Client.getUser:getUser·p0.90          sample         5.541           ms/op
Client.getUser:getUser·p0.95          sample         6.791           ms/op
Client.getUser:getUser·p0.99          sample        10.062           ms/op
Client.getUser:getUser·p0.999         sample        20.624           ms/op
Client.getUser:getUser·p0.9999        sample        21.594           ms/op
Client.getUser:getUser·p1.00          sample        21.594           ms/op
Client.listUser                       sample  1885  16.979 ± 0.179   ms/op
Client.listUser:listUser·p0.00        sample         5.980           ms/op
Client.listUser:listUser·p0.50        sample        16.843           ms/op
Client.listUser:listUser·p0.90        sample        19.117           ms/op
Client.listUser:listUser·p0.95        sample        19.694           ms/op
Client.listUser:listUser·p0.99        sample        26.115           ms/op
Client.listUser:listUser·p0.999       sample        29.884           ms/op
Client.listUser:listUser·p0.9999      sample        30.900           ms/op
Client.listUser:listUser·p1.00        sample        30.900           ms/op
