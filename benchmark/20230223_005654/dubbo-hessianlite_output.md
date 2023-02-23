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
# Warmup Iteration   1: 1.054 ops/ms
Iteration   1: 2.244 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.244 ops/ms


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
# Warmup Iteration   1: 3.069 ops/ms
Iteration   1: 6.576 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.576 ops/ms


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
# Warmup Iteration   1: 2.223 ops/ms
Iteration   1: 4.414 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.414 ops/ms


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
# Warmup Iteration   1: 0.924 ops/ms
Iteration   1: 1.702 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.702 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 19.124 ±(99.9%) 0.348 ms/op
Iteration   1: 7.470 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.470 ms/op


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
# Warmup Iteration   1: 7.495 ±(99.9%) 0.112 ms/op
Iteration   1: 4.358 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.358 ms/op


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
# Warmup Iteration   1: 7.932 ±(99.9%) 0.105 ms/op
Iteration   1: 4.732 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.732 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 30.127 ±(99.9%) 0.527 ms/op
Iteration   1: 16.262 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.262 ms/op


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
# Warmup Iteration   1: 10.920 ±(99.9%) 0.358 ms/op
Iteration   1: 5.454 ±(99.9%) 0.126 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   7.152 ms/op
                 createUser·p0.95:   8.798 ms/op
                 createUser·p0.99:   20.775 ms/op
                 createUser·p0.999:  26.345 ms/op
                 createUser·p0.9999: 26.673 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5858
  mean =      5.454 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 3011 
    [ 5.000,  7.500) = 2474 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     20.775 ms/op
     p(99.9000) =     26.345 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 7.812 ±(99.9%) 0.270 ms/op
Iteration   1: 4.386 ±(99.9%) 0.103 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   4.063 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   6.939 ms/op
                 existUser·p0.99:   13.920 ms/op
                 existUser·p0.999:  32.860 ms/op
                 existUser·p0.9999: 33.620 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7341
  mean =      4.386 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 740 
    [ 2.500,  5.000) = 5687 
    [ 5.000,  7.500) = 585 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =     13.920 ms/op
     p(99.9000) =     32.860 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 11.717 ±(99.9%) 0.335 ms/op
Iteration   1: 4.555 ±(99.9%) 0.061 ms/op
                 getUser·p0.00:   2.159 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.578 ms/op
                 getUser·p0.99:   11.237 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 20.120 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7016
  mean =      4.555 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 5882 
    [ 5.000,  7.500) = 870 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.159 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =     11.237 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 28.882 ±(99.9%) 0.682 ms/op
Iteration   1: 17.258 ±(99.9%) 0.166 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   17.236 ms/op
                 listUser·p0.90:   18.842 ms/op
                 listUser·p0.95:   19.595 ms/op
                 listUser·p0.99:   21.660 ms/op
                 listUser·p0.999:  35.052 ms/op
                 listUser·p0.9999: 36.569 ms/op
                 listUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1826
  mean =     17.258 ±(99.9%) 0.166 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 941 
    [17.500, 20.000) = 695 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.437 ms/op
     p(50.0000) =     17.236 ms/op
     p(90.0000) =     18.842 ms/op
     p(95.0000) =     19.595 ms/op
     p(99.0000) =     21.660 ms/op
     p(99.9000) =     35.052 ms/op
     p(99.9900) =     36.569 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.244          ops/ms
Client.existUser                       thrpt         6.576          ops/ms
Client.getUser                         thrpt         4.414          ops/ms
Client.listUser                        thrpt         1.702          ops/ms
Client.createUser                       avgt         7.470           ms/op
Client.existUser                        avgt         4.358           ms/op
Client.getUser                          avgt         4.732           ms/op
Client.listUser                         avgt        16.262           ms/op
Client.createUser                     sample  5858   5.454 ± 0.126   ms/op
Client.createUser:createUser·p0.00    sample         1.540           ms/op
Client.createUser:createUser·p0.50    sample         4.678           ms/op
Client.createUser:createUser·p0.90    sample         7.152           ms/op
Client.createUser:createUser·p0.95    sample         8.798           ms/op
Client.createUser:createUser·p0.99    sample        20.775           ms/op
Client.createUser:createUser·p0.999   sample        26.345           ms/op
Client.createUser:createUser·p0.9999  sample        26.673           ms/op
Client.createUser:createUser·p1.00    sample        26.673           ms/op
Client.existUser                      sample  7341   4.386 ± 0.103   ms/op
Client.existUser:existUser·p0.00      sample         0.883           ms/op
Client.existUser:existUser·p0.50      sample         4.063           ms/op
Client.existUser:existUser·p0.90      sample         5.349           ms/op
Client.existUser:existUser·p0.95      sample         6.939           ms/op
Client.existUser:existUser·p0.99      sample        13.920           ms/op
Client.existUser:existUser·p0.999     sample        32.860           ms/op
Client.existUser:existUser·p0.9999    sample        33.620           ms/op
Client.existUser:existUser·p1.00      sample        33.620           ms/op
Client.getUser                        sample  7016   4.555 ± 0.061   ms/op
Client.getUser:getUser·p0.00          sample         2.159           ms/op
Client.getUser:getUser·p0.50          sample         4.133           ms/op
Client.getUser:getUser·p0.90          sample         5.620           ms/op
Client.getUser:getUser·p0.95          sample         6.578           ms/op
Client.getUser:getUser·p0.99          sample        11.237           ms/op
Client.getUser:getUser·p0.999         sample        19.169           ms/op
Client.getUser:getUser·p0.9999        sample        20.120           ms/op
Client.getUser:getUser·p1.00          sample        20.120           ms/op
Client.listUser                       sample  1826  17.258 ± 0.166   ms/op
Client.listUser:listUser·p0.00        sample         2.437           ms/op
Client.listUser:listUser·p0.50        sample        17.236           ms/op
Client.listUser:listUser·p0.90        sample        18.842           ms/op
Client.listUser:listUser·p0.95        sample        19.595           ms/op
Client.listUser:listUser·p0.99        sample        21.660           ms/op
Client.listUser:listUser·p0.999       sample        35.052           ms/op
Client.listUser:listUser·p0.9999      sample        36.569           ms/op
Client.listUser:listUser·p1.00        sample        36.569           ms/op
