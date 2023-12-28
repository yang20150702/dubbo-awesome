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
# Warmup Iteration   1: 2.194 ops/ms
Iteration   1: 5.830 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.830 ops/ms


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
# Warmup Iteration   1: 6.318 ops/ms
Iteration   1: 12.698 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.698 ops/ms


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
# Warmup Iteration   1: 4.452 ops/ms
Iteration   1: 8.936 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.936 ops/ms


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
# Warmup Iteration   1: 1.981 ops/ms
Iteration   1: 3.582 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.582 ops/ms


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
# Warmup Iteration   1: 5.329 ±(99.9%) 0.078 ms/op
Iteration   1: 3.437 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.437 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.052 ms/op
Iteration   1: 2.063 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.063 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.057 ms/op
Iteration   1: 3.273 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.273 ms/op


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
# Warmup Iteration   1: 12.288 ±(99.9%) 0.240 ms/op
Iteration   1: 8.004 ±(99.9%) 0.138 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.004 ms/op


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.130 ms/op
Iteration   1: 2.894 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   2.761 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   6.009 ms/op
                 createUser·p0.999:  16.841 ms/op
                 createUser·p0.9999: 17.134 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11051
  mean =      2.894 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 2205 
    [ 2.500,  3.750) = 8190 
    [ 3.750,  5.000) = 497 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      6.009 ms/op
     p(99.9000) =     16.841 ms/op
     p(99.9900) =     17.134 ms/op
     p(99.9990) =     17.138 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.071 ms/op
Iteration   1: 1.950 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  14.500 ms/op
                 existUser·p0.9999: 14.680 ms/op
                 existUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16397
  mean =      1.950 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 381 
    [ 1.250,  2.500) = 14798 
    [ 2.500,  3.750) = 1015 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.128 ms/op
Iteration   1: 3.013 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.311 ms/op
                 getUser·p0.999:  6.546 ms/op
                 getUser·p0.9999: 7.916 ms/op
                 getUser·p1.00:   7.954 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10632
  mean =      3.013 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 25 
    [1.500, 2.000) = 486 
    [2.000, 2.500) = 1864 
    [2.500, 3.000) = 2959 
    [3.000, 3.500) = 3286 
    [3.500, 4.000) = 1464 
    [4.000, 4.500) = 298 
    [4.500, 5.000) = 102 
    [5.000, 5.500) = 60 
    [5.500, 6.000) = 63 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.311 ms/op
     p(99.9000) =      6.546 ms/op
     p(99.9900) =      7.916 ms/op
     p(99.9990) =      7.954 ms/op
     p(99.9999) =      7.954 ms/op
    p(100.0000) =      7.954 ms/op


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
# Warmup Iteration   1: 12.353 ±(99.9%) 0.451 ms/op
Iteration   1: 8.649 ±(99.9%) 0.135 ms/op
                 listUser·p0.00:   3.207 ms/op
                 listUser·p0.50:   8.200 ms/op
                 listUser·p0.90:   11.583 ms/op
                 listUser·p0.95:   12.648 ms/op
                 listUser·p0.99:   16.468 ms/op
                 listUser·p0.999:  25.404 ms/op
                 listUser·p0.9999: 28.213 ms/op
                 listUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3732
  mean =      8.649 ±(99.9%) 0.135 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 80 
    [ 5.000,  7.500) = 1298 
    [ 7.500, 10.000) = 1461 
    [10.000, 12.500) = 689 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.207 ms/op
     p(50.0000) =      8.200 ms/op
     p(90.0000) =     11.583 ms/op
     p(95.0000) =     12.648 ms/op
     p(99.0000) =     16.468 ms/op
     p(99.9000) =     25.404 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.830          ops/ms
Client.existUser                       thrpt         12.698          ops/ms
Client.getUser                         thrpt          8.936          ops/ms
Client.listUser                        thrpt          3.582          ops/ms
Client.createUser                       avgt          3.437           ms/op
Client.existUser                        avgt          2.063           ms/op
Client.getUser                          avgt          3.273           ms/op
Client.listUser                         avgt          8.004           ms/op
Client.createUser                     sample  11051   2.894 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.087           ms/op
Client.createUser:createUser·p0.50    sample          2.761           ms/op
Client.createUser:createUser·p0.90    sample          3.441           ms/op
Client.createUser:createUser·p0.95    sample          3.834           ms/op
Client.createUser:createUser·p0.99    sample          6.009           ms/op
Client.createUser:createUser·p0.999   sample         16.841           ms/op
Client.createUser:createUser·p0.9999  sample         17.134           ms/op
Client.createUser:createUser·p1.00    sample         17.138           ms/op
Client.existUser                      sample  16397   1.950 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.882           ms/op
Client.existUser:existUser·p0.50      sample          1.870           ms/op
Client.existUser:existUser·p0.90      sample          2.408           ms/op
Client.existUser:existUser·p0.95      sample          2.617           ms/op
Client.existUser:existUser·p0.99      sample          4.047           ms/op
Client.existUser:existUser·p0.999     sample         14.500           ms/op
Client.existUser:existUser·p0.9999    sample         14.680           ms/op
Client.existUser:existUser·p1.00      sample         14.680           ms/op
Client.getUser                        sample  10632   3.013 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.126           ms/op
Client.getUser:getUser·p0.50          sample          2.998           ms/op
Client.getUser:getUser·p0.90          sample          3.781           ms/op
Client.getUser:getUser·p0.95          sample          4.010           ms/op
Client.getUser:getUser·p0.99          sample          5.311           ms/op
Client.getUser:getUser·p0.999         sample          6.546           ms/op
Client.getUser:getUser·p0.9999        sample          7.916           ms/op
Client.getUser:getUser·p1.00          sample          7.954           ms/op
Client.listUser                       sample   3732   8.649 ± 0.135   ms/op
Client.listUser:listUser·p0.00        sample          3.207           ms/op
Client.listUser:listUser·p0.50        sample          8.200           ms/op
Client.listUser:listUser·p0.90        sample         11.583           ms/op
Client.listUser:listUser·p0.95        sample         12.648           ms/op
Client.listUser:listUser·p0.99        sample         16.468           ms/op
Client.listUser:listUser·p0.999       sample         25.404           ms/op
Client.listUser:listUser·p0.9999      sample         28.213           ms/op
Client.listUser:listUser·p1.00        sample         28.213           ms/op
