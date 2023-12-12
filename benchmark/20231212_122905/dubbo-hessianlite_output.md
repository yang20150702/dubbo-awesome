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
# Warmup Iteration   1: 1.990 ops/ms
Iteration   1: 6.503 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.503 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.263 ops/ms
Iteration   1: 13.462 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.462 ops/ms


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
# Warmup Iteration   1: 4.224 ops/ms
Iteration   1: 8.521 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.521 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.060 ops/ms
Iteration   1: 3.259 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.259 ops/ms


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
# Warmup Iteration   1: 5.453 ±(99.9%) 0.081 ms/op
Iteration   1: 3.180 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.180 ms/op


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
# Warmup Iteration   1: 3.681 ±(99.9%) 0.037 ms/op
Iteration   1: 2.133 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.133 ms/op


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.053 ms/op
Iteration   1: 3.184 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.184 ms/op


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
# Warmup Iteration   1: 12.843 ±(99.9%) 0.318 ms/op
Iteration   1: 8.380 ±(99.9%) 0.124 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.380 ms/op


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
# Warmup Iteration   1: 4.957 ±(99.9%) 0.107 ms/op
Iteration   1: 2.909 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.750 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.970 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  13.894 ms/op
                 createUser·p0.9999: 14.937 ms/op
                 createUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10996
  mean =      2.909 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 3508 
    [ 2.500,  3.750) = 6615 
    [ 3.750,  5.000) = 592 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.750 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.970 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     14.937 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.083 ms/op
Iteration   1: 1.786 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.245 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   4.553 ms/op
                 existUser·p0.999:  14.287 ms/op
                 existUser·p0.9999: 15.303 ms/op
                 existUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17919
  mean =      1.786 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1275 
    [ 1.250,  2.500) = 16022 
    [ 2.500,  3.750) = 401 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      4.553 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     15.303 ms/op
     p(99.9990) =     15.991 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.113 ms/op
Iteration   1: 3.590 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.251 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 9.863 ms/op
                 getUser·p1.00:   9.863 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8930
  mean =      3.590 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 17 
    [ 1.500,  2.000) = 89 
    [ 2.000,  2.500) = 465 
    [ 2.500,  3.000) = 1199 
    [ 3.000,  3.500) = 2419 
    [ 3.500,  4.000) = 2353 
    [ 4.000,  4.500) = 1604 
    [ 4.500,  5.000) = 516 
    [ 5.000,  5.500) = 130 
    [ 5.500,  6.000) = 37 
    [ 6.000,  6.500) = 17 
    [ 6.500,  7.000) = 23 
    [ 7.000,  7.500) = 27 
    [ 7.500,  8.000) = 17 
    [ 8.000,  8.500) = 8 
    [ 8.500,  9.000) = 7 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.251 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =      9.863 ms/op
     p(99.9990) =      9.863 ms/op
     p(99.9999) =      9.863 ms/op
    p(100.0000) =      9.863 ms/op


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
# Warmup Iteration   1: 12.618 ±(99.9%) 0.430 ms/op
Iteration   1: 9.320 ±(99.9%) 0.142 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   9.028 ms/op
                 listUser·p0.90:   12.419 ms/op
                 listUser·p0.95:   14.347 ms/op
                 listUser·p0.99:   18.481 ms/op
                 listUser·p0.999:  22.306 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3426
  mean =      9.320 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 34 
    [ 5.000,  7.500) = 698 
    [ 7.500, 10.000) = 1755 
    [10.000, 12.500) = 614 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      9.028 ms/op
     p(90.0000) =     12.419 ms/op
     p(95.0000) =     14.347 ms/op
     p(99.0000) =     18.481 ms/op
     p(99.9000) =     22.306 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.503          ops/ms
Client.existUser                       thrpt         13.462          ops/ms
Client.getUser                         thrpt          8.521          ops/ms
Client.listUser                        thrpt          3.259          ops/ms
Client.createUser                       avgt          3.180           ms/op
Client.existUser                        avgt          2.133           ms/op
Client.getUser                          avgt          3.184           ms/op
Client.listUser                         avgt          8.380           ms/op
Client.createUser                     sample  10996   2.909 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          0.810           ms/op
Client.createUser:createUser·p0.50    sample          2.750           ms/op
Client.createUser:createUser·p0.90    sample          3.584           ms/op
Client.createUser:createUser·p0.95    sample          3.970           ms/op
Client.createUser:createUser·p0.99    sample          7.397           ms/op
Client.createUser:createUser·p0.999   sample         13.894           ms/op
Client.createUser:createUser·p0.9999  sample         14.937           ms/op
Client.createUser:createUser·p1.00    sample         14.942           ms/op
Client.existUser                      sample  17919   1.786 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.686           ms/op
Client.existUser:existUser·p0.50      sample          1.702           ms/op
Client.existUser:existUser·p0.90      sample          2.245           ms/op
Client.existUser:existUser·p0.95      sample          2.408           ms/op
Client.existUser:existUser·p0.99      sample          4.553           ms/op
Client.existUser:existUser·p0.999     sample         14.287           ms/op
Client.existUser:existUser·p0.9999    sample         15.303           ms/op
Client.existUser:existUser·p1.00      sample         15.991           ms/op
Client.getUser                        sample   8930   3.590 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          1.239           ms/op
Client.getUser:getUser·p0.50          sample          3.547           ms/op
Client.getUser:getUser·p0.90          sample          4.456           ms/op
Client.getUser:getUser·p0.95          sample          4.719           ms/op
Client.getUser:getUser·p0.99          sample          6.251           ms/op
Client.getUser:getUser·p0.999         sample          8.520           ms/op
Client.getUser:getUser·p0.9999        sample          9.863           ms/op
Client.getUser:getUser·p1.00          sample          9.863           ms/op
Client.listUser                       sample   3426   9.320 ± 0.142   ms/op
Client.listUser:listUser·p0.00        sample          1.778           ms/op
Client.listUser:listUser·p0.50        sample          9.028           ms/op
Client.listUser:listUser·p0.90        sample         12.419           ms/op
Client.listUser:listUser·p0.95        sample         14.347           ms/op
Client.listUser:listUser·p0.99        sample         18.481           ms/op
Client.listUser:listUser·p0.999       sample         22.306           ms/op
Client.listUser:listUser·p0.9999      sample         25.919           ms/op
Client.listUser:listUser·p1.00        sample         25.919           ms/op
