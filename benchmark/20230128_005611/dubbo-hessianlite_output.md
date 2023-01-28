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
# Warmup Iteration   1: 1.070 ops/ms
Iteration   1: 2.798 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.798 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.705 ops/ms
Iteration   1: 5.231 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.231 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.808 ops/ms
Iteration   1: 4.395 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.395 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.932 ops/ms
Iteration   1: 1.297 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.297 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 19.807 ±(99.9%) 0.251 ms/op
Iteration   1: 7.700 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.700 ms/op


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
# Warmup Iteration   1: 7.554 ±(99.9%) 0.085 ms/op
Iteration   1: 3.716 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.716 ms/op


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
# Warmup Iteration   1: 9.071 ±(99.9%) 0.115 ms/op
Iteration   1: 4.646 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.646 ms/op


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
# Warmup Iteration   1: 31.825 ±(99.9%) 0.344 ms/op
Iteration   1: 16.547 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.547 ms/op


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
# Warmup Iteration   1: 11.918 ±(99.9%) 0.367 ms/op
Iteration   1: 5.623 ±(99.9%) 0.090 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   7.379 ms/op
                 createUser·p0.99:   19.825 ms/op
                 createUser·p0.999:  21.113 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5745
  mean =      5.623 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 1832 
    [ 5.000,  7.500) = 3691 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      7.379 ms/op
     p(99.0000) =     19.825 ms/op
     p(99.9000) =     21.113 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 7.006 ±(99.9%) 0.203 ms/op
Iteration   1: 3.866 ±(99.9%) 0.071 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   8.847 ms/op
                 existUser·p0.99:   12.410 ms/op
                 existUser·p0.999:  15.237 ms/op
                 existUser·p0.9999: 15.598 ms/op
                 existUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8317
  mean =      3.866 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 969 
    [ 2.500,  3.750) = 4336 
    [ 3.750,  5.000) = 2388 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 146 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.410 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     15.598 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 9.734 ±(99.9%) 0.354 ms/op
Iteration   1: 5.542 ±(99.9%) 0.079 ms/op
                 getUser·p0.00:   2.650 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   6.676 ms/op
                 getUser·p0.95:   7.726 ms/op
                 getUser·p0.99:   13.737 ms/op
                 getUser·p0.999:  21.135 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5756
  mean =      5.542 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1938 
    [ 5.000,  7.500) = 3522 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.650 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.726 ms/op
     p(99.0000) =     13.737 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 30.514 ±(99.9%) 0.812 ms/op
Iteration   1: 16.707 ±(99.9%) 0.212 ms/op
                 listUser·p0.00:   5.120 ms/op
                 listUser·p0.50:   16.187 ms/op
                 listUser·p0.90:   19.071 ms/op
                 listUser·p0.95:   22.004 ms/op
                 listUser·p0.99:   28.312 ms/op
                 listUser·p0.999:  30.837 ms/op
                 listUser·p0.9999: 30.867 ms/op
                 listUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1924
  mean =     16.707 ±(99.9%) 0.212 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 1423 
    [17.500, 20.000) = 202 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.120 ms/op
     p(50.0000) =     16.187 ms/op
     p(90.0000) =     19.071 ms/op
     p(95.0000) =     22.004 ms/op
     p(99.0000) =     28.312 ms/op
     p(99.9000) =     30.837 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.798          ops/ms
Client.existUser                       thrpt         5.231          ops/ms
Client.getUser                         thrpt         4.395          ops/ms
Client.listUser                        thrpt         1.297          ops/ms
Client.createUser                       avgt         7.700           ms/op
Client.existUser                        avgt         3.716           ms/op
Client.getUser                          avgt         4.646           ms/op
Client.listUser                         avgt        16.547           ms/op
Client.createUser                     sample  5745   5.623 ± 0.090   ms/op
Client.createUser:createUser·p0.00    sample         0.483           ms/op
Client.createUser:createUser·p0.50    sample         5.571           ms/op
Client.createUser:createUser·p0.90    sample         6.930           ms/op
Client.createUser:createUser·p0.95    sample         7.379           ms/op
Client.createUser:createUser·p0.99    sample        19.825           ms/op
Client.createUser:createUser·p0.999   sample        21.113           ms/op
Client.createUser:createUser·p0.9999  sample        21.823           ms/op
Client.createUser:createUser·p1.00    sample        21.823           ms/op
Client.existUser                      sample  8317   3.866 ± 0.071   ms/op
Client.existUser:existUser·p0.00      sample         0.994           ms/op
Client.existUser:existUser·p0.50      sample         3.641           ms/op
Client.existUser:existUser·p0.90      sample         4.497           ms/op
Client.existUser:existUser·p0.95      sample         8.847           ms/op
Client.existUser:existUser·p0.99      sample        12.410           ms/op
Client.existUser:existUser·p0.999     sample        15.237           ms/op
Client.existUser:existUser·p0.9999    sample        15.598           ms/op
Client.existUser:existUser·p1.00      sample        15.598           ms/op
Client.getUser                        sample  5756   5.542 ± 0.079   ms/op
Client.getUser:getUser·p0.00          sample         2.650           ms/op
Client.getUser:getUser·p0.50          sample         5.259           ms/op
Client.getUser:getUser·p0.90          sample         6.676           ms/op
Client.getUser:getUser·p0.95          sample         7.726           ms/op
Client.getUser:getUser·p0.99          sample        13.737           ms/op
Client.getUser:getUser·p0.999         sample        21.135           ms/op
Client.getUser:getUser·p0.9999        sample        21.529           ms/op
Client.getUser:getUser·p1.00          sample        21.529           ms/op
Client.listUser                       sample  1924  16.707 ± 0.212   ms/op
Client.listUser:listUser·p0.00        sample         5.120           ms/op
Client.listUser:listUser·p0.50        sample        16.187           ms/op
Client.listUser:listUser·p0.90        sample        19.071           ms/op
Client.listUser:listUser·p0.95        sample        22.004           ms/op
Client.listUser:listUser·p0.99        sample        28.312           ms/op
Client.listUser:listUser·p0.999       sample        30.837           ms/op
Client.listUser:listUser·p0.9999      sample        30.867           ms/op
Client.listUser:listUser·p1.00        sample        30.867           ms/op
