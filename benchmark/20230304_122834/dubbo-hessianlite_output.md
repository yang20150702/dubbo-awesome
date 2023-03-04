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
# Warmup Iteration   1: 1.179 ops/ms
Iteration   1: 2.689 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.689 ops/ms


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
# Warmup Iteration   1: 3.227 ops/ms
Iteration   1: 6.648 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.648 ops/ms


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
# Warmup Iteration   1: 1.807 ops/ms
Iteration   1: 4.940 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.940 ops/ms


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
# Warmup Iteration   1: 0.897 ops/ms
Iteration   1: 1.386 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.386 ops/ms


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
# Warmup Iteration   1: 17.328 ±(99.9%) 0.266 ms/op
Iteration   1: 8.263 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.263 ms/op


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
# Warmup Iteration   1: 7.736 ±(99.9%) 0.080 ms/op
Iteration   1: 3.771 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.771 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.818 ±(99.9%) 0.147 ms/op
Iteration   1: 4.769 ±(99.9%) 0.062 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.769 ms/op


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
# Warmup Iteration   1: 27.652 ±(99.9%) 0.466 ms/op
Iteration   1: 17.482 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.482 ms/op


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
# Warmup Iteration   1: 10.982 ±(99.9%) 0.385 ms/op
Iteration   1: 6.086 ±(99.9%) 0.089 ms/op
                 createUser·p0.00:   0.490 ms/op
                 createUser·p0.50:   5.751 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   14.336 ms/op
                 createUser·p0.999:  21.379 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5286
  mean =      6.086 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 503 
    [ 5.000,  7.500) = 4482 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      5.751 ms/op
     p(90.0000) =      6.504 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     14.336 ms/op
     p(99.9000) =     21.379 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 7.518 ±(99.9%) 0.220 ms/op
Iteration   1: 4.438 ±(99.9%) 0.101 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   6.954 ms/op
                 existUser·p0.99:   19.169 ms/op
                 existUser·p0.999:  31.090 ms/op
                 existUser·p0.9999: 31.687 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7206
  mean =      4.438 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 266 
    [ 2.500,  5.000) = 6412 
    [ 5.000,  7.500) = 216 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      6.954 ms/op
     p(99.0000) =     19.169 ms/op
     p(99.9000) =     31.090 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 9.960 ±(99.9%) 0.349 ms/op
Iteration   1: 4.682 ±(99.9%) 0.072 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   6.036 ms/op
                 getUser·p0.95:   7.007 ms/op
                 getUser·p0.99:   14.260 ms/op
                 getUser·p0.999:  21.146 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6831
  mean =      4.682 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 5271 
    [ 5.000,  7.500) = 1215 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      6.036 ms/op
     p(95.0000) =      7.007 ms/op
     p(99.0000) =     14.260 ms/op
     p(99.9000) =     21.146 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 26.941 ±(99.9%) 0.772 ms/op
Iteration   1: 15.972 ±(99.9%) 0.156 ms/op
                 listUser·p0.00:   8.847 ms/op
                 listUser·p0.50:   15.499 ms/op
                 listUser·p0.90:   17.170 ms/op
                 listUser·p0.95:   19.661 ms/op
                 listUser·p0.99:   25.884 ms/op
                 listUser·p0.999:  34.188 ms/op
                 listUser·p0.9999: 38.666 ms/op
                 listUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2006
  mean =     15.972 ±(99.9%) 0.156 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 452 
    [15.000, 17.500) = 1369 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      8.847 ms/op
     p(50.0000) =     15.499 ms/op
     p(90.0000) =     17.170 ms/op
     p(95.0000) =     19.661 ms/op
     p(99.0000) =     25.884 ms/op
     p(99.9000) =     34.188 ms/op
     p(99.9900) =     38.666 ms/op
     p(99.9990) =     38.666 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.689          ops/ms
Client.existUser                       thrpt         6.648          ops/ms
Client.getUser                         thrpt         4.940          ops/ms
Client.listUser                        thrpt         1.386          ops/ms
Client.createUser                       avgt         8.263           ms/op
Client.existUser                        avgt         3.771           ms/op
Client.getUser                          avgt         4.769           ms/op
Client.listUser                         avgt        17.482           ms/op
Client.createUser                     sample  5286   6.086 ± 0.089   ms/op
Client.createUser:createUser·p0.00    sample         0.490           ms/op
Client.createUser:createUser·p0.50    sample         5.751           ms/op
Client.createUser:createUser·p0.90    sample         6.504           ms/op
Client.createUser:createUser·p0.95    sample         8.552           ms/op
Client.createUser:createUser·p0.99    sample        14.336           ms/op
Client.createUser:createUser·p0.999   sample        21.379           ms/op
Client.createUser:createUser·p0.9999  sample        22.118           ms/op
Client.createUser:createUser·p1.00    sample        22.118           ms/op
Client.existUser                      sample  7206   4.438 ± 0.101   ms/op
Client.existUser:existUser·p0.00      sample         0.904           ms/op
Client.existUser:existUser·p0.50      sample         4.100           ms/op
Client.existUser:existUser·p0.90      sample         4.530           ms/op
Client.existUser:existUser·p0.95      sample         6.954           ms/op
Client.existUser:existUser·p0.99      sample        19.169           ms/op
Client.existUser:existUser·p0.999     sample        31.090           ms/op
Client.existUser:existUser·p0.9999    sample        31.687           ms/op
Client.existUser:existUser·p1.00      sample        31.687           ms/op
Client.getUser                        sample  6831   4.682 ± 0.072   ms/op
Client.getUser:getUser·p0.00          sample         1.534           ms/op
Client.getUser:getUser·p0.50          sample         4.383           ms/op
Client.getUser:getUser·p0.90          sample         6.036           ms/op
Client.getUser:getUser·p0.95          sample         7.007           ms/op
Client.getUser:getUser·p0.99          sample        14.260           ms/op
Client.getUser:getUser·p0.999         sample        21.146           ms/op
Client.getUser:getUser·p0.9999        sample        21.496           ms/op
Client.getUser:getUser·p1.00          sample        21.496           ms/op
Client.listUser                       sample  2006  15.972 ± 0.156   ms/op
Client.listUser:listUser·p0.00        sample         8.847           ms/op
Client.listUser:listUser·p0.50        sample        15.499           ms/op
Client.listUser:listUser·p0.90        sample        17.170           ms/op
Client.listUser:listUser·p0.95        sample        19.661           ms/op
Client.listUser:listUser·p0.99        sample        25.884           ms/op
Client.listUser:listUser·p0.999       sample        34.188           ms/op
Client.listUser:listUser·p0.9999      sample        38.666           ms/op
Client.listUser:listUser·p1.00        sample        38.666           ms/op
