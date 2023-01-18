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
# Warmup Iteration   1: 1.019 ops/ms
Iteration   1: 2.679 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.679 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.140 ops/ms
Iteration   1: 6.561 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.561 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.620 ops/ms
Iteration   1: 3.885 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.885 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.839 ops/ms
Iteration   1: 1.218 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.218 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 14.149 ±(99.9%) 0.201 ms/op
Iteration   1: 8.207 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.207 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ±(99.9%) 0.083 ms/op
Iteration   1: 3.924 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.924 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.141 ±(99.9%) 0.213 ms/op
Iteration   1: 6.435 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.435 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.141 ±(99.9%) 0.607 ms/op
Iteration   1: 19.000 ±(99.9%) 0.172 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.000 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.290 ±(99.9%) 0.355 ms/op
Iteration   1: 6.151 ±(99.9%) 0.145 ms/op
                 createUser·p0.00:   2.363 ms/op
                 createUser·p0.50:   6.799 ms/op
                 createUser·p0.90:   7.569 ms/op
                 createUser·p0.95:   8.651 ms/op
                 createUser·p0.99:   16.801 ms/op
                 createUser·p0.999:  35.375 ms/op
                 createUser·p0.9999: 35.979 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5218
  mean =      6.151 ±(99.9%) 0.145 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 1824 
    [ 5.000,  7.500) = 2714 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      6.799 ms/op
     p(90.0000) =      7.569 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     16.801 ms/op
     p(99.9000) =     35.375 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 7.048 ±(99.9%) 0.183 ms/op
Iteration   1: 4.283 ±(99.9%) 0.083 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   7.487 ms/op
                 existUser·p0.99:   11.764 ms/op
                 existUser·p0.999:  21.939 ms/op
                 existUser·p0.9999: 22.118 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7465
  mean =      4.283 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 927 
    [ 2.500,  5.000) = 5718 
    [ 5.000,  7.500) = 449 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      7.487 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     21.939 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 11.040 ±(99.9%) 0.404 ms/op
Iteration   1: 5.064 ±(99.9%) 0.060 ms/op
                 getUser·p0.00:   1.985 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   5.751 ms/op
                 getUser·p0.95:   7.586 ms/op
                 getUser·p0.99:   11.718 ms/op
                 getUser·p0.999:  19.351 ms/op
                 getUser·p0.9999: 19.857 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6476
  mean =      5.064 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 23 
    [ 2.500,  3.750) = 318 
    [ 3.750,  5.000) = 3886 
    [ 5.000,  6.250) = 1759 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     11.718 ms/op
     p(99.9000) =     19.351 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 29.390 ±(99.9%) 0.937 ms/op
Iteration   1: 18.458 ±(99.9%) 0.333 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   18.055 ms/op
                 listUser·p0.90:   21.365 ms/op
                 listUser·p0.95:   28.000 ms/op
                 listUser·p0.99:   34.374 ms/op
                 listUser·p0.999:  41.959 ms/op
                 listUser·p0.9999: 42.009 ms/op
                 listUser·p1.00:   42.009 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1749
  mean =     18.458 ±(99.9%) 0.333 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5 
    [ 5.000, 10.000) = 22 
    [10.000, 15.000) = 216 
    [15.000, 20.000) = 1284 
    [20.000, 25.000) = 85 
    [25.000, 30.000) = 95 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.662 ms/op
     p(50.0000) =     18.055 ms/op
     p(90.0000) =     21.365 ms/op
     p(95.0000) =     28.000 ms/op
     p(99.0000) =     34.374 ms/op
     p(99.9000) =     41.959 ms/op
     p(99.9900) =     42.009 ms/op
     p(99.9990) =     42.009 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.679          ops/ms
Client.existUser                       thrpt         6.561          ops/ms
Client.getUser                         thrpt         3.885          ops/ms
Client.listUser                        thrpt         1.218          ops/ms
Client.createUser                       avgt         8.207           ms/op
Client.existUser                        avgt         3.924           ms/op
Client.getUser                          avgt         6.435           ms/op
Client.listUser                         avgt        19.000           ms/op
Client.createUser                     sample  5218   6.151 ± 0.145   ms/op
Client.createUser:createUser·p0.00    sample         2.363           ms/op
Client.createUser:createUser·p0.50    sample         6.799           ms/op
Client.createUser:createUser·p0.90    sample         7.569           ms/op
Client.createUser:createUser·p0.95    sample         8.651           ms/op
Client.createUser:createUser·p0.99    sample        16.801           ms/op
Client.createUser:createUser·p0.999   sample        35.375           ms/op
Client.createUser:createUser·p0.9999  sample        35.979           ms/op
Client.createUser:createUser·p1.00    sample        35.979           ms/op
Client.existUser                      sample  7465   4.283 ± 0.083   ms/op
Client.existUser:existUser·p0.00      sample         0.571           ms/op
Client.existUser:existUser·p0.50      sample         4.153           ms/op
Client.existUser:existUser·p0.90      sample         5.251           ms/op
Client.existUser:existUser·p0.95      sample         7.487           ms/op
Client.existUser:existUser·p0.99      sample        11.764           ms/op
Client.existUser:existUser·p0.999     sample        21.939           ms/op
Client.existUser:existUser·p0.9999    sample        22.118           ms/op
Client.existUser:existUser·p1.00      sample        22.118           ms/op
Client.getUser                        sample  6476   5.064 ± 0.060   ms/op
Client.getUser:getUser·p0.00          sample         1.985           ms/op
Client.getUser:getUser·p0.50          sample         4.809           ms/op
Client.getUser:getUser·p0.90          sample         5.751           ms/op
Client.getUser:getUser·p0.95          sample         7.586           ms/op
Client.getUser:getUser·p0.99          sample        11.718           ms/op
Client.getUser:getUser·p0.999         sample        19.351           ms/op
Client.getUser:getUser·p0.9999        sample        19.857           ms/op
Client.getUser:getUser·p1.00          sample        19.857           ms/op
Client.listUser                       sample  1749  18.458 ± 0.333   ms/op
Client.listUser:listUser·p0.00        sample         2.662           ms/op
Client.listUser:listUser·p0.50        sample        18.055           ms/op
Client.listUser:listUser·p0.90        sample        21.365           ms/op
Client.listUser:listUser·p0.95        sample        28.000           ms/op
Client.listUser:listUser·p0.99        sample        34.374           ms/op
Client.listUser:listUser·p0.999       sample        41.959           ms/op
Client.listUser:listUser·p0.9999      sample        42.009           ms/op
Client.listUser:listUser·p1.00        sample        42.009           ms/op
