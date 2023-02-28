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
# Warmup Iteration   1: 1.124 ops/ms
Iteration   1: 2.316 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.316 ops/ms


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
# Warmup Iteration   1: 2.337 ops/ms
Iteration   1: 6.039 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.039 ops/ms


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
# Warmup Iteration   1: 1.953 ops/ms
Iteration   1: 4.358 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.358 ops/ms


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
# Warmup Iteration   1: 0.913 ops/ms
Iteration   1: 1.168 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.168 ops/ms


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
# Warmup Iteration   1: 19.013 ±(99.9%) 0.407 ms/op
Iteration   1: 7.150 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.150 ms/op


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
# Warmup Iteration   1: 8.207 ±(99.9%) 0.091 ms/op
Iteration   1: 3.924 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.924 ms/op


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
# Warmup Iteration   1: 9.765 ±(99.9%) 0.144 ms/op
Iteration   1: 5.252 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.252 ms/op


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
# Warmup Iteration   1: 27.708 ±(99.9%) 0.548 ms/op
Iteration   1: 16.302 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.302 ms/op


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
# Warmup Iteration   1: 13.095 ±(99.9%) 0.334 ms/op
Iteration   1: 6.219 ±(99.9%) 0.176 ms/op
                 createUser·p0.00:   2.830 ms/op
                 createUser·p0.50:   6.038 ms/op
                 createUser·p0.90:   7.449 ms/op
                 createUser·p0.95:   9.251 ms/op
                 createUser·p0.99:   20.513 ms/op
                 createUser·p0.999:  42.992 ms/op
                 createUser·p0.9999: 51.708 ms/op
                 createUser·p1.00:   51.708 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5166
  mean =      6.219 ±(99.9%) 0.176 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1545 
    [ 5.000, 10.000) = 3368 
    [10.000, 15.000) = 125 
    [15.000, 20.000) = 40 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 30 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.830 ms/op
     p(50.0000) =      6.038 ms/op
     p(90.0000) =      7.449 ms/op
     p(95.0000) =      9.251 ms/op
     p(99.0000) =     20.513 ms/op
     p(99.9000) =     42.992 ms/op
     p(99.9900) =     51.708 ms/op
     p(99.9990) =     51.708 ms/op
     p(99.9999) =     51.708 ms/op
    p(100.0000) =     51.708 ms/op


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
# Warmup Iteration   1: 7.717 ±(99.9%) 0.256 ms/op
Iteration   1: 3.834 ±(99.9%) 0.078 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   3.994 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   6.371 ms/op
                 existUser·p0.99:   11.659 ms/op
                 existUser·p0.999:  25.509 ms/op
                 existUser·p0.9999: 29.360 ms/op
                 existUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8506
  mean =      3.834 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2084 
    [ 2.500,  5.000) = 5597 
    [ 5.000,  7.500) = 569 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      6.371 ms/op
     p(99.0000) =     11.659 ms/op
     p(99.9000) =     25.509 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 10.851 ±(99.9%) 0.374 ms/op
Iteration   1: 4.851 ±(99.9%) 0.081 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.618 ms/op
                 getUser·p0.99:   17.138 ms/op
                 getUser·p0.999:  20.568 ms/op
                 getUser·p0.9999: 21.135 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6662
  mean =      4.851 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 5542 
    [ 5.000,  7.500) = 840 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.759 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.618 ms/op
     p(99.0000) =     17.138 ms/op
     p(99.9000) =     20.568 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 28.764 ±(99.9%) 0.876 ms/op
Iteration   1: 20.882 ±(99.9%) 0.367 ms/op
                 listUser·p0.00:   6.324 ms/op
                 listUser·p0.50:   19.005 ms/op
                 listUser·p0.90:   26.526 ms/op
                 listUser·p0.95:   28.467 ms/op
                 listUser·p0.99:   38.607 ms/op
                 listUser·p0.999:  43.045 ms/op
                 listUser·p0.9999: 43.188 ms/op
                 listUser·p1.00:   43.188 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1544
  mean =     20.882 ±(99.9%) 0.367 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 2 
    [10.000, 15.000) = 38 
    [15.000, 20.000) = 901 
    [20.000, 25.000) = 339 
    [25.000, 30.000) = 200 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      6.324 ms/op
     p(50.0000) =     19.005 ms/op
     p(90.0000) =     26.526 ms/op
     p(95.0000) =     28.467 ms/op
     p(99.0000) =     38.607 ms/op
     p(99.9000) =     43.045 ms/op
     p(99.9900) =     43.188 ms/op
     p(99.9990) =     43.188 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.316          ops/ms
Client.existUser                       thrpt         6.039          ops/ms
Client.getUser                         thrpt         4.358          ops/ms
Client.listUser                        thrpt         1.168          ops/ms
Client.createUser                       avgt         7.150           ms/op
Client.existUser                        avgt         3.924           ms/op
Client.getUser                          avgt         5.252           ms/op
Client.listUser                         avgt        16.302           ms/op
Client.createUser                     sample  5166   6.219 ± 0.176   ms/op
Client.createUser:createUser·p0.00    sample         2.830           ms/op
Client.createUser:createUser·p0.50    sample         6.038           ms/op
Client.createUser:createUser·p0.90    sample         7.449           ms/op
Client.createUser:createUser·p0.95    sample         9.251           ms/op
Client.createUser:createUser·p0.99    sample        20.513           ms/op
Client.createUser:createUser·p0.999   sample        42.992           ms/op
Client.createUser:createUser·p0.9999  sample        51.708           ms/op
Client.createUser:createUser·p1.00    sample        51.708           ms/op
Client.existUser                      sample  8506   3.834 ± 0.078   ms/op
Client.existUser:existUser·p0.00      sample         0.632           ms/op
Client.existUser:existUser·p0.50      sample         3.994           ms/op
Client.existUser:existUser·p0.90      sample         4.981           ms/op
Client.existUser:existUser·p0.95      sample         6.371           ms/op
Client.existUser:existUser·p0.99      sample        11.659           ms/op
Client.existUser:existUser·p0.999     sample        25.509           ms/op
Client.existUser:existUser·p0.9999    sample        29.360           ms/op
Client.existUser:existUser·p1.00      sample        29.360           ms/op
Client.getUser                        sample  6662   4.851 ± 0.081   ms/op
Client.getUser:getUser·p0.00          sample         1.759           ms/op
Client.getUser:getUser·p0.50          sample         4.415           ms/op
Client.getUser:getUser·p0.90          sample         5.571           ms/op
Client.getUser:getUser·p0.95          sample         6.618           ms/op
Client.getUser:getUser·p0.99          sample        17.138           ms/op
Client.getUser:getUser·p0.999         sample        20.568           ms/op
Client.getUser:getUser·p0.9999        sample        21.135           ms/op
Client.getUser:getUser·p1.00          sample        21.135           ms/op
Client.listUser                       sample  1544  20.882 ± 0.367   ms/op
Client.listUser:listUser·p0.00        sample         6.324           ms/op
Client.listUser:listUser·p0.50        sample        19.005           ms/op
Client.listUser:listUser·p0.90        sample        26.526           ms/op
Client.listUser:listUser·p0.95        sample        28.467           ms/op
Client.listUser:listUser·p0.99        sample        38.607           ms/op
Client.listUser:listUser·p0.999       sample        43.045           ms/op
Client.listUser:listUser·p0.9999      sample        43.188           ms/op
Client.listUser:listUser·p1.00        sample        43.188           ms/op
