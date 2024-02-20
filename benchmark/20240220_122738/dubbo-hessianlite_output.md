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
# Warmup Iteration   1: 2.269 ops/ms
Iteration   1: 6.463 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.463 ops/ms


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
# Warmup Iteration   1: 5.188 ops/ms
Iteration   1: 13.648 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.648 ops/ms


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
# Warmup Iteration   1: 4.731 ops/ms
Iteration   1: 9.246 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.246 ops/ms


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
# Warmup Iteration   1: 2.113 ops/ms
Iteration   1: 3.976 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.976 ops/ms


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
# Warmup Iteration   1: 5.947 ±(99.9%) 0.141 ms/op
Iteration   1: 3.077 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.077 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.031 ms/op
Iteration   1: 1.848 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.848 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.055 ms/op
Iteration   1: 2.702 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.702 ms/op


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
# Warmup Iteration   1: 11.699 ±(99.9%) 0.239 ms/op
Iteration   1: 7.663 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.663 ms/op


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
# Warmup Iteration   1: 5.252 ±(99.9%) 0.117 ms/op
Iteration   1: 2.727 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   2.470 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  15.666 ms/op
                 createUser·p0.9999: 15.794 ms/op
                 createUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11899
  mean =      2.727 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 6152 
    [ 2.500,  3.750) = 4830 
    [ 3.750,  5.000) = 688 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     15.666 ms/op
     p(99.9900) =     15.794 ms/op
     p(99.9990) =     15.794 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 2.954 ±(99.9%) 0.065 ms/op
Iteration   1: 1.741 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.452 ms/op
                 existUser·p0.50:   1.614 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   4.673 ms/op
                 existUser·p0.999:  18.830 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18358
  mean =      1.741 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1585 
    [ 1.250,  2.500) = 15866 
    [ 2.500,  3.750) = 656 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      1.614 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      4.673 ms/op
     p(99.9000) =     18.830 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.180 ms/op
Iteration   1: 2.988 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.884 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.280 ms/op
                 getUser·p0.999:  7.118 ms/op
                 getUser·p0.9999: 7.298 ms/op
                 getUser·p1.00:   7.299 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10720
  mean =      2.988 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 6 
    [1.000, 1.500) = 34 
    [1.500, 2.000) = 260 
    [2.000, 2.500) = 2506 
    [2.500, 3.000) = 3213 
    [3.000, 3.500) = 2566 
    [3.500, 4.000) = 1475 
    [4.000, 4.500) = 363 
    [4.500, 5.000) = 122 
    [5.000, 5.500) = 92 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 34 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.280 ms/op
     p(99.9000) =      7.118 ms/op
     p(99.9900) =      7.298 ms/op
     p(99.9990) =      7.299 ms/op
     p(99.9999) =      7.299 ms/op
    p(100.0000) =      7.299 ms/op


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
# Warmup Iteration   1: 12.189 ±(99.9%) 0.400 ms/op
Iteration   1: 7.485 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   7.119 ms/op
                 listUser·p0.90:   9.601 ms/op
                 listUser·p0.95:   10.946 ms/op
                 listUser·p0.99:   16.695 ms/op
                 listUser·p0.999:  19.980 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4257
  mean =      7.485 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 200 
    [ 5.000,  7.500) = 2328 
    [ 7.500, 10.000) = 1385 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      7.119 ms/op
     p(90.0000) =      9.601 ms/op
     p(95.0000) =     10.946 ms/op
     p(99.0000) =     16.695 ms/op
     p(99.9000) =     19.980 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.463          ops/ms
Client.existUser                       thrpt         13.648          ops/ms
Client.getUser                         thrpt          9.246          ops/ms
Client.listUser                        thrpt          3.976          ops/ms
Client.createUser                       avgt          3.077           ms/op
Client.existUser                        avgt          1.848           ms/op
Client.getUser                          avgt          2.702           ms/op
Client.listUser                         avgt          7.663           ms/op
Client.createUser                     sample  11899   2.727 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.141           ms/op
Client.createUser:createUser·p0.50    sample          2.470           ms/op
Client.createUser:createUser·p0.90    sample          3.547           ms/op
Client.createUser:createUser·p0.95    sample          4.047           ms/op
Client.createUser:createUser·p0.99    sample          6.349           ms/op
Client.createUser:createUser·p0.999   sample         15.666           ms/op
Client.createUser:createUser·p0.9999  sample         15.794           ms/op
Client.createUser:createUser·p1.00    sample         15.794           ms/op
Client.existUser                      sample  18358   1.741 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.452           ms/op
Client.existUser:existUser·p0.50      sample          1.614           ms/op
Client.existUser:existUser·p0.90      sample          2.195           ms/op
Client.existUser:existUser·p0.95      sample          2.499           ms/op
Client.existUser:existUser·p0.99      sample          4.673           ms/op
Client.existUser:existUser·p0.999     sample         18.830           ms/op
Client.existUser:existUser·p0.9999    sample         19.038           ms/op
Client.existUser:existUser·p1.00      sample         19.038           ms/op
Client.getUser                        sample  10720   2.988 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.874           ms/op
Client.getUser:getUser·p0.50          sample          2.884           ms/op
Client.getUser:getUser·p0.90          sample          3.826           ms/op
Client.getUser:getUser·p0.95          sample          4.108           ms/op
Client.getUser:getUser·p0.99          sample          5.280           ms/op
Client.getUser:getUser·p0.999         sample          7.118           ms/op
Client.getUser:getUser·p0.9999        sample          7.298           ms/op
Client.getUser:getUser·p1.00          sample          7.299           ms/op
Client.listUser                       sample   4257   7.485 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample          1.296           ms/op
Client.listUser:listUser·p0.50        sample          7.119           ms/op
Client.listUser:listUser·p0.90        sample          9.601           ms/op
Client.listUser:listUser·p0.95        sample         10.946           ms/op
Client.listUser:listUser·p0.99        sample         16.695           ms/op
Client.listUser:listUser·p0.999       sample         19.980           ms/op
Client.listUser:listUser·p0.9999      sample         21.430           ms/op
Client.listUser:listUser·p1.00        sample         21.430           ms/op
