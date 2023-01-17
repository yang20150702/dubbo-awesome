# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.784 ops/ms
Iteration   1: 1.800 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.800 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:21
# Fork: 1 of 1
# Warmup Iteration   1: 1.702 ops/ms
Iteration   1: 6.355 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.355 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.417 ops/ms
Iteration   1: 3.624 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.624 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 0.795 ops/ms
Iteration   1: 1.062 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.062 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 20.653 ±(99.9%) 0.423 ms/op
Iteration   1: 10.843 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.843 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 10.363 ±(99.9%) 0.131 ms/op
Iteration   1: 4.459 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.459 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.058 ±(99.9%) 0.216 ms/op
Iteration   1: 5.683 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.683 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 33.588 ±(99.9%) 0.488 ms/op
Iteration   1: 19.393 ±(99.9%) 0.153 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 17.279 ±(99.9%) 0.775 ms/op
Iteration   1: 7.228 ±(99.9%) 0.165 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   6.496 ms/op
                 createUser·p0.90:   9.028 ms/op
                 createUser·p0.95:   14.942 ms/op
                 createUser·p0.99:   23.855 ms/op
                 createUser·p0.999:  25.731 ms/op
                 createUser·p0.9999: 25.985 ms/op
                 createUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4459
  mean =      7.228 ±(99.9%) 0.165 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 507 
    [ 5.000,  7.500) = 3066 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      6.496 ms/op
     p(90.0000) =      9.028 ms/op
     p(95.0000) =     14.942 ms/op
     p(99.0000) =     23.855 ms/op
     p(99.9000) =     25.731 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.414 ±(99.9%) 0.293 ms/op
Iteration   1: 5.580 ±(99.9%) 0.101 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   5.472 ms/op
                 existUser·p0.90:   6.431 ms/op
                 existUser·p0.95:   9.503 ms/op
                 existUser·p0.99:   16.902 ms/op
                 existUser·p0.999:  18.817 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5754
  mean =      5.580 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 443 
    [ 2.500,  3.750) = 379 
    [ 3.750,  5.000) = 286 
    [ 5.000,  6.250) = 3823 
    [ 6.250,  7.500) = 424 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      9.503 ms/op
     p(99.0000) =     16.902 ms/op
     p(99.9000) =     18.817 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 13.825 ±(99.9%) 0.587 ms/op
Iteration   1: 5.221 ±(99.9%) 0.116 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   9.437 ms/op
                 getUser·p0.99:   19.788 ms/op
                 getUser·p0.999:  27.722 ms/op
                 getUser·p0.9999: 28.312 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6188
  mean =      5.221 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 4251 
    [ 5.000,  7.500) = 1481 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      9.437 ms/op
     p(99.0000) =     19.788 ms/op
     p(99.9000) =     27.722 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 30.530 ±(99.9%) 1.069 ms/op
Iteration   1: 17.569 ±(99.9%) 0.362 ms/op
                 listUser·p0.00:   4.743 ms/op
                 listUser·p0.50:   15.319 ms/op
                 listUser·p0.90:   24.576 ms/op
                 listUser·p0.95:   27.912 ms/op
                 listUser·p0.99:   33.020 ms/op
                 listUser·p0.999:  35.127 ms/op
                 listUser·p0.9999: 35.127 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1830
  mean =     17.569 ±(99.9%) 0.362 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 524 
    [15.000, 17.500) = 598 
    [17.500, 20.000) = 222 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      4.743 ms/op
     p(50.0000) =     15.319 ms/op
     p(90.0000) =     24.576 ms/op
     p(95.0000) =     27.912 ms/op
     p(99.0000) =     33.020 ms/op
     p(99.9000) =     35.127 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:01:28

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.800          ops/ms
Client.existUser                       thrpt         6.355          ops/ms
Client.getUser                         thrpt         3.624          ops/ms
Client.listUser                        thrpt         1.062          ops/ms
Client.createUser                       avgt        10.843           ms/op
Client.existUser                        avgt         4.459           ms/op
Client.getUser                          avgt         5.683           ms/op
Client.listUser                         avgt        19.393           ms/op
Client.createUser                     sample  4459   7.228 ± 0.165   ms/op
Client.createUser:createUser·p0.00    sample         1.606           ms/op
Client.createUser:createUser·p0.50    sample         6.496           ms/op
Client.createUser:createUser·p0.90    sample         9.028           ms/op
Client.createUser:createUser·p0.95    sample        14.942           ms/op
Client.createUser:createUser·p0.99    sample        23.855           ms/op
Client.createUser:createUser·p0.999   sample        25.731           ms/op
Client.createUser:createUser·p0.9999  sample        25.985           ms/op
Client.createUser:createUser·p1.00    sample        25.985           ms/op
Client.existUser                      sample  5754   5.580 ± 0.101   ms/op
Client.existUser:existUser·p0.00      sample         0.916           ms/op
Client.existUser:existUser·p0.50      sample         5.472           ms/op
Client.existUser:existUser·p0.90      sample         6.431           ms/op
Client.existUser:existUser·p0.95      sample         9.503           ms/op
Client.existUser:existUser·p0.99      sample        16.902           ms/op
Client.existUser:existUser·p0.999     sample        18.817           ms/op
Client.existUser:existUser·p0.9999    sample        19.235           ms/op
Client.existUser:existUser·p1.00      sample        19.235           ms/op
Client.getUser                        sample  6188   5.221 ± 0.116   ms/op
Client.getUser:getUser·p0.00          sample         1.393           ms/op
Client.getUser:getUser·p0.50          sample         4.555           ms/op
Client.getUser:getUser·p0.90          sample         6.398           ms/op
Client.getUser:getUser·p0.95          sample         9.437           ms/op
Client.getUser:getUser·p0.99          sample        19.788           ms/op
Client.getUser:getUser·p0.999         sample        27.722           ms/op
Client.getUser:getUser·p0.9999        sample        28.312           ms/op
Client.getUser:getUser·p1.00          sample        28.312           ms/op
Client.listUser                       sample  1830  17.569 ± 0.362   ms/op
Client.listUser:listUser·p0.00        sample         4.743           ms/op
Client.listUser:listUser·p0.50        sample        15.319           ms/op
Client.listUser:listUser·p0.90        sample        24.576           ms/op
Client.listUser:listUser·p0.95        sample        27.912           ms/op
Client.listUser:listUser·p0.99        sample        33.020           ms/op
Client.listUser:listUser·p0.999       sample        35.127           ms/op
Client.listUser:listUser·p0.9999      sample        35.127           ms/op
Client.listUser:listUser·p1.00        sample        35.127           ms/op
