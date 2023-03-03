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
# Warmup Iteration   1: 0.980 ops/ms
Iteration   1: 1.947 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.947 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:21
# Fork: 1 of 1
# Warmup Iteration   1: 1.848 ops/ms
Iteration   1: 7.109 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.109 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.396 ops/ms
Iteration   1: 3.861 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.861 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.733 ops/ms
Iteration   1: 1.311 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.311 ops/ms


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
# Warmup Iteration   1: 18.708 ±(99.9%) 0.293 ms/op
Iteration   1: 9.763 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.763 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.381 ±(99.9%) 0.294 ms/op
Iteration   1: 5.314 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.314 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.821 ±(99.9%) 0.209 ms/op
Iteration   1: 6.133 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.133 ms/op


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
# Warmup Iteration   1: 34.065 ±(99.9%) 0.757 ms/op
Iteration   1: 20.104 ±(99.9%) 0.156 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.104 ms/op


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
# Warmup Iteration   1: 14.254 ±(99.9%) 0.445 ms/op
Iteration   1: 6.982 ±(99.9%) 0.140 ms/op
                 createUser·p0.00:   2.642 ms/op
                 createUser·p0.50:   6.627 ms/op
                 createUser·p0.90:   8.602 ms/op
                 createUser·p0.95:   10.923 ms/op
                 createUser·p0.99:   16.220 ms/op
                 createUser·p0.999:  35.258 ms/op
                 createUser·p0.9999: 35.324 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4601
  mean =      6.982 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 470 
    [ 5.000,  7.500) = 3326 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.642 ms/op
     p(50.0000) =      6.627 ms/op
     p(90.0000) =      8.602 ms/op
     p(95.0000) =     10.923 ms/op
     p(99.0000) =     16.220 ms/op
     p(99.9000) =     35.258 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     35.324 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 9.128 ±(99.9%) 0.291 ms/op
Iteration   1: 5.524 ±(99.9%) 0.100 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   5.333 ms/op
                 existUser·p0.90:   5.865 ms/op
                 existUser·p0.95:   7.990 ms/op
                 existUser·p0.99:   13.208 ms/op
                 existUser·p0.999:  31.832 ms/op
                 existUser·p0.9999: 31.949 ms/op
                 existUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5786
  mean =      5.524 ±(99.9%) 0.100 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184 
    [ 2.500,  5.000) = 880 
    [ 5.000,  7.500) = 4374 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      7.990 ms/op
     p(99.0000) =     13.208 ms/op
     p(99.9000) =     31.832 ms/op
     p(99.9900) =     31.949 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 15.222 ±(99.9%) 0.509 ms/op
Iteration   1: 5.064 ±(99.9%) 0.079 ms/op
                 getUser·p0.00:   2.232 ms/op
                 getUser·p0.50:   4.719 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.622 ms/op
                 getUser·p0.99:   13.573 ms/op
                 getUser·p0.999:  27.492 ms/op
                 getUser·p0.9999: 28.541 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6293
  mean =      5.064 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 4339 
    [ 5.000,  7.500) = 1794 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.622 ms/op
     p(99.0000) =     13.573 ms/op
     p(99.9000) =     27.492 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 33.159 ±(99.9%) 1.032 ms/op
Iteration   1: 23.458 ±(99.9%) 0.496 ms/op
                 listUser·p0.00:   11.502 ms/op
                 listUser·p0.50:   21.955 ms/op
                 listUser·p0.90:   28.882 ms/op
                 listUser·p0.95:   33.882 ms/op
                 listUser·p0.99:   50.562 ms/op
                 listUser·p0.999:  58.404 ms/op
                 listUser·p0.9999: 58.655 ms/op
                 listUser·p1.00:   58.655 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1382
  mean =     23.458 ±(99.9%) 0.496 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 23 
    [15.000, 20.000) = 243 
    [20.000, 25.000) = 746 
    [25.000, 30.000) = 266 
    [30.000, 35.000) = 64 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =     11.502 ms/op
     p(50.0000) =     21.955 ms/op
     p(90.0000) =     28.882 ms/op
     p(95.0000) =     33.882 ms/op
     p(99.0000) =     50.562 ms/op
     p(99.9000) =     58.404 ms/op
     p(99.9900) =     58.655 ms/op
     p(99.9990) =     58.655 ms/op
     p(99.9999) =     58.655 ms/op
    p(100.0000) =     58.655 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.947          ops/ms
Client.existUser                       thrpt         7.109          ops/ms
Client.getUser                         thrpt         3.861          ops/ms
Client.listUser                        thrpt         1.311          ops/ms
Client.createUser                       avgt         9.763           ms/op
Client.existUser                        avgt         5.314           ms/op
Client.getUser                          avgt         6.133           ms/op
Client.listUser                         avgt        20.104           ms/op
Client.createUser                     sample  4601   6.982 ± 0.140   ms/op
Client.createUser:createUser·p0.00    sample         2.642           ms/op
Client.createUser:createUser·p0.50    sample         6.627           ms/op
Client.createUser:createUser·p0.90    sample         8.602           ms/op
Client.createUser:createUser·p0.95    sample        10.923           ms/op
Client.createUser:createUser·p0.99    sample        16.220           ms/op
Client.createUser:createUser·p0.999   sample        35.258           ms/op
Client.createUser:createUser·p0.9999  sample        35.324           ms/op
Client.createUser:createUser·p1.00    sample        35.324           ms/op
Client.existUser                      sample  5786   5.524 ± 0.100   ms/op
Client.existUser:existUser·p0.00      sample         1.243           ms/op
Client.existUser:existUser·p0.50      sample         5.333           ms/op
Client.existUser:existUser·p0.90      sample         5.865           ms/op
Client.existUser:existUser·p0.95      sample         7.990           ms/op
Client.existUser:existUser·p0.99      sample        13.208           ms/op
Client.existUser:existUser·p0.999     sample        31.832           ms/op
Client.existUser:existUser·p0.9999    sample        31.949           ms/op
Client.existUser:existUser·p1.00      sample        31.949           ms/op
Client.getUser                        sample  6293   5.064 ± 0.079   ms/op
Client.getUser:getUser·p0.00          sample         2.232           ms/op
Client.getUser:getUser·p0.50          sample         4.719           ms/op
Client.getUser:getUser·p0.90          sample         5.677           ms/op
Client.getUser:getUser·p0.95          sample         6.622           ms/op
Client.getUser:getUser·p0.99          sample        13.573           ms/op
Client.getUser:getUser·p0.999         sample        27.492           ms/op
Client.getUser:getUser·p0.9999        sample        28.541           ms/op
Client.getUser:getUser·p1.00          sample        28.541           ms/op
Client.listUser                       sample  1382  23.458 ± 0.496   ms/op
Client.listUser:listUser·p0.00        sample        11.502           ms/op
Client.listUser:listUser·p0.50        sample        21.955           ms/op
Client.listUser:listUser·p0.90        sample        28.882           ms/op
Client.listUser:listUser·p0.95        sample        33.882           ms/op
Client.listUser:listUser·p0.99        sample        50.562           ms/op
Client.listUser:listUser·p0.999       sample        58.404           ms/op
Client.listUser:listUser·p0.9999      sample        58.655           ms/op
Client.listUser:listUser·p1.00        sample        58.655           ms/op
