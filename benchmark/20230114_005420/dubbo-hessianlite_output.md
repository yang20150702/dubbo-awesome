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
# Warmup Iteration   1: 0.832 ops/ms
Iteration   1: 1.747 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.747 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.116 ops/ms
Iteration   1: 5.315 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.315 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.728 ops/ms
Iteration   1: 3.293 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.293 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 0.819 ops/ms
Iteration   1: 1.192 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.192 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 24.330 ±(99.9%) 0.333 ms/op
Iteration   1: 10.472 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.472 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 12.499 ±(99.9%) 0.281 ms/op
Iteration   1: 6.714 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.714 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.759 ±(99.9%) 0.301 ms/op
Iteration   1: 8.393 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.393 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 34.520 ±(99.9%) 0.715 ms/op
Iteration   1: 23.442 ±(99.9%) 0.134 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.442 ms/op


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
# Warmup Iteration   1: 17.592 ±(99.9%) 0.651 ms/op
Iteration   1: 8.760 ±(99.9%) 0.195 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   8.520 ms/op
                 createUser·p0.90:   13.943 ms/op
                 createUser·p0.95:   15.416 ms/op
                 createUser·p0.99:   22.779 ms/op
                 createUser·p0.999:  26.389 ms/op
                 createUser·p0.9999: 26.903 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3670
  mean =      8.760 ±(99.9%) 0.195 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 371 
    [ 5.000,  7.500) = 1090 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      8.520 ms/op
     p(90.0000) =     13.943 ms/op
     p(95.0000) =     15.416 ms/op
     p(99.0000) =     22.779 ms/op
     p(99.9000) =     26.389 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.335 ±(99.9%) 0.319 ms/op
Iteration   1: 5.216 ±(99.9%) 0.098 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   5.961 ms/op
                 existUser·p0.95:   8.651 ms/op
                 existUser·p0.99:   16.701 ms/op
                 existUser·p0.999:  23.182 ms/op
                 existUser·p0.9999: 24.871 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6132
  mean =      5.216 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 3717 
    [ 5.000,  7.500) = 1994 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.961 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     16.701 ms/op
     p(99.9000) =     23.182 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 14.004 ±(99.9%) 0.491 ms/op
Iteration   1: 5.640 ±(99.9%) 0.100 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.521 ms/op
                 getUser·p0.95:   7.594 ms/op
                 getUser·p0.99:   19.025 ms/op
                 getUser·p0.999:  26.355 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5669
  mean =      5.640 ±(99.9%) 0.100 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 1698 
    [ 5.000,  7.500) = 3675 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.594 ms/op
     p(99.0000) =     19.025 ms/op
     p(99.9000) =     26.355 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 35.941 ±(99.9%) 1.430 ms/op
Iteration   1: 25.811 ±(99.9%) 0.640 ms/op
                 listUser·p0.00:   5.890 ms/op
                 listUser·p0.50:   25.068 ms/op
                 listUser·p0.90:   32.702 ms/op
                 listUser·p0.95:   36.661 ms/op
                 listUser·p0.99:   50.856 ms/op
                 listUser·p0.999:  58.685 ms/op
                 listUser·p0.9999: 61.080 ms/op
                 listUser·p1.00:   61.080 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1241
  mean =     25.811 ±(99.9%) 0.640 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 13 
    [10.000, 15.000) = 55 
    [15.000, 20.000) = 64 
    [20.000, 25.000) = 478 
    [25.000, 30.000) = 312 
    [30.000, 35.000) = 241 
    [35.000, 40.000) = 38 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 10 
    [50.000, 55.000) = 20 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      5.890 ms/op
     p(50.0000) =     25.068 ms/op
     p(90.0000) =     32.702 ms/op
     p(95.0000) =     36.661 ms/op
     p(99.0000) =     50.856 ms/op
     p(99.9000) =     58.685 ms/op
     p(99.9900) =     61.080 ms/op
     p(99.9990) =     61.080 ms/op
     p(99.9999) =     61.080 ms/op
    p(100.0000) =     61.080 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.747          ops/ms
Client.existUser                       thrpt         5.315          ops/ms
Client.getUser                         thrpt         3.293          ops/ms
Client.listUser                        thrpt         1.192          ops/ms
Client.createUser                       avgt        10.472           ms/op
Client.existUser                        avgt         6.714           ms/op
Client.getUser                          avgt         8.393           ms/op
Client.listUser                         avgt        23.442           ms/op
Client.createUser                     sample  3670   8.760 ± 0.195   ms/op
Client.createUser:createUser·p0.00    sample         1.626           ms/op
Client.createUser:createUser·p0.50    sample         8.520           ms/op
Client.createUser:createUser·p0.90    sample        13.943           ms/op
Client.createUser:createUser·p0.95    sample        15.416           ms/op
Client.createUser:createUser·p0.99    sample        22.779           ms/op
Client.createUser:createUser·p0.999   sample        26.389           ms/op
Client.createUser:createUser·p0.9999  sample        26.903           ms/op
Client.createUser:createUser·p1.00    sample        26.903           ms/op
Client.existUser                      sample  6132   5.216 ± 0.098   ms/op
Client.existUser:existUser·p0.00      sample         1.208           ms/op
Client.existUser:existUser·p0.50      sample         4.686           ms/op
Client.existUser:existUser·p0.90      sample         5.961           ms/op
Client.existUser:existUser·p0.95      sample         8.651           ms/op
Client.existUser:existUser·p0.99      sample        16.701           ms/op
Client.existUser:existUser·p0.999     sample        23.182           ms/op
Client.existUser:existUser·p0.9999    sample        24.871           ms/op
Client.existUser:existUser·p1.00      sample        24.871           ms/op
Client.getUser                        sample  5669   5.640 ± 0.100   ms/op
Client.getUser:getUser·p0.00          sample         1.753           ms/op
Client.getUser:getUser·p0.50          sample         5.136           ms/op
Client.getUser:getUser·p0.90          sample         6.521           ms/op
Client.getUser:getUser·p0.95          sample         7.594           ms/op
Client.getUser:getUser·p0.99          sample        19.025           ms/op
Client.getUser:getUser·p0.999         sample        26.355           ms/op
Client.getUser:getUser·p0.9999        sample        26.903           ms/op
Client.getUser:getUser·p1.00          sample        26.903           ms/op
Client.listUser                       sample  1241  25.811 ± 0.640   ms/op
Client.listUser:listUser·p0.00        sample         5.890           ms/op
Client.listUser:listUser·p0.50        sample        25.068           ms/op
Client.listUser:listUser·p0.90        sample        32.702           ms/op
Client.listUser:listUser·p0.95        sample        36.661           ms/op
Client.listUser:listUser·p0.99        sample        50.856           ms/op
Client.listUser:listUser·p0.999       sample        58.685           ms/op
Client.listUser:listUser·p0.9999      sample        61.080           ms/op
Client.listUser:listUser·p1.00        sample        61.080           ms/op
