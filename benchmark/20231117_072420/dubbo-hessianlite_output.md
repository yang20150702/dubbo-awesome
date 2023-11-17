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
# Warmup Iteration   1: 2.288 ops/ms
Iteration   1: 5.627 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.627 ops/ms


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
# Warmup Iteration   1: 6.474 ops/ms
Iteration   1: 11.665 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.665 ops/ms


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
# Warmup Iteration   1: 4.633 ops/ms
Iteration   1: 9.552 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.552 ops/ms


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
# Warmup Iteration   1: 2.438 ops/ms
Iteration   1: 4.019 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.019 ops/ms


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
# Warmup Iteration   1: 6.133 ±(99.9%) 0.101 ms/op
Iteration   1: 3.355 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.355 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.055 ms/op
Iteration   1: 2.088 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.088 ms/op


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.064 ms/op
Iteration   1: 2.842 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.842 ms/op


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
# Warmup Iteration   1: 12.230 ±(99.9%) 0.231 ms/op
Iteration   1: 7.895 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.895 ms/op


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
# Warmup Iteration   1: 4.769 ±(99.9%) 0.095 ms/op
Iteration   1: 2.871 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.354 ms/op
                 createUser·p0.99:   7.576 ms/op
                 createUser·p0.999:  12.382 ms/op
                 createUser·p0.9999: 14.690 ms/op
                 createUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11128
  mean =      2.871 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 3761 
    [ 2.500,  3.750) = 6400 
    [ 3.750,  5.000) = 584 
    [ 5.000,  6.250) = 222 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.354 ms/op
     p(99.0000) =      7.576 ms/op
     p(99.9000) =     12.382 ms/op
     p(99.9900) =     14.690 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.031 ±(99.9%) 0.064 ms/op
Iteration   1: 2.197 ±(99.9%) 0.176 ms/op
                 existUser·p0.00:   0.281 ms/op
                 existUser·p0.50:   1.819 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   4.436 ms/op
                 existUser·p0.999:  139.461 ms/op
                 existUser·p0.9999: 141.887 ms/op
                 existUser·p1.00:   142.606 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14573
  mean =      2.197 ±(99.9%) 0.176 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 14518 
    [ 12.500,  25.000) = 23 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 32 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      4.436 ms/op
     p(99.9000) =    139.461 ms/op
     p(99.9900) =    141.887 ms/op
     p(99.9990) =    142.606 ms/op
     p(99.9999) =    142.606 ms/op
    p(100.0000) =    142.606 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.089 ms/op
Iteration   1: 2.800 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.738 ms/op
                 getUser·p0.99:   5.204 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 12.922 ms/op
                 getUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11386
  mean =      2.800 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 4529 
    [ 2.500,  3.750) = 6299 
    [ 3.750,  5.000) = 395 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.738 ms/op
     p(99.0000) =      5.204 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     12.922 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


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
# Warmup Iteration   1: 10.949 ±(99.9%) 0.352 ms/op
Iteration   1: 8.066 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   3.428 ms/op
                 listUser·p0.50:   7.684 ms/op
                 listUser·p0.90:   10.846 ms/op
                 listUser·p0.95:   11.684 ms/op
                 listUser·p0.99:   13.779 ms/op
                 listUser·p0.999:  19.341 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3956
  mean =      8.066 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 63 
    [ 5.000,  7.500) = 1767 
    [ 7.500, 10.000) = 1453 
    [10.000, 12.500) = 584 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.428 ms/op
     p(50.0000) =      7.684 ms/op
     p(90.0000) =     10.846 ms/op
     p(95.0000) =     11.684 ms/op
     p(99.0000) =     13.779 ms/op
     p(99.9000) =     19.341 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           5.627          ops/ms
Client.existUser                       thrpt          11.665          ops/ms
Client.getUser                         thrpt           9.552          ops/ms
Client.listUser                        thrpt           4.019          ops/ms
Client.createUser                       avgt           3.355           ms/op
Client.existUser                        avgt           2.088           ms/op
Client.getUser                          avgt           2.842           ms/op
Client.listUser                         avgt           7.895           ms/op
Client.createUser                     sample  11128    2.871 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample           1.053           ms/op
Client.createUser:createUser·p0.50    sample           2.650           ms/op
Client.createUser:createUser·p0.90    sample           3.625           ms/op
Client.createUser:createUser·p0.95    sample           4.354           ms/op
Client.createUser:createUser·p0.99    sample           7.576           ms/op
Client.createUser:createUser·p0.999   sample          12.382           ms/op
Client.createUser:createUser·p0.9999  sample          14.690           ms/op
Client.createUser:createUser·p1.00    sample          14.746           ms/op
Client.existUser                      sample  14573    2.197 ± 0.176   ms/op
Client.existUser:existUser·p0.00      sample           0.281           ms/op
Client.existUser:existUser·p0.50      sample           1.819           ms/op
Client.existUser:existUser·p0.90      sample           2.408           ms/op
Client.existUser:existUser·p0.95      sample           2.634           ms/op
Client.existUser:existUser·p0.99      sample           4.436           ms/op
Client.existUser:existUser·p0.999     sample         139.461           ms/op
Client.existUser:existUser·p0.9999    sample         141.887           ms/op
Client.existUser:existUser·p1.00      sample         142.606           ms/op
Client.getUser                        sample  11386    2.800 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample           1.037           ms/op
Client.getUser:getUser·p0.50          sample           2.597           ms/op
Client.getUser:getUser·p0.90          sample           3.490           ms/op
Client.getUser:getUser·p0.95          sample           3.738           ms/op
Client.getUser:getUser·p0.99          sample           5.204           ms/op
Client.getUser:getUser·p0.999         sample          12.730           ms/op
Client.getUser:getUser·p0.9999        sample          12.922           ms/op
Client.getUser:getUser·p1.00          sample          12.927           ms/op
Client.listUser                       sample   3956    8.066 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample           3.428           ms/op
Client.listUser:listUser·p0.50        sample           7.684           ms/op
Client.listUser:listUser·p0.90        sample          10.846           ms/op
Client.listUser:listUser·p0.95        sample          11.684           ms/op
Client.listUser:listUser·p0.99        sample          13.779           ms/op
Client.listUser:listUser·p0.999       sample          19.341           ms/op
Client.listUser:listUser·p0.9999      sample          22.348           ms/op
Client.listUser:listUser·p1.00        sample          22.348           ms/op
