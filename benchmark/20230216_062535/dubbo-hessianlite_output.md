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
# Warmup Iteration   1: 0.255 ops/ms
Iteration   1: 0.718 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  0.718 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:36
# Fork: 1 of 1
# Warmup Iteration   1: 1.097 ops/ms
Iteration   1: 2.187 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.187 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 0.818 ops/ms
Iteration   1: 1.711 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  1.711 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 0.481 ops/ms
Iteration   1: 0.624 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.624 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 39.306 ±(99.9%) 1.101 ms/op
Iteration   1: 27.537 ±(99.9%) 0.233 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  27.537 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 22.498 ±(99.9%) 0.402 ms/op
Iteration   1: 13.498 ±(99.9%) 0.133 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.498 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 37.185 ±(99.9%) 0.953 ms/op
Iteration   1: 15.740 ±(99.9%) 0.168 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  15.740 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 49.158 ±(99.9%) 1.784 ms/op
Iteration   1: 40.761 ±(99.9%) 0.840 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  40.761 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:33
# Fork: 1 of 1
# Warmup Iteration   1: 27.588 ±(99.9%) 1.138 ms/op
Iteration   1: 19.159 ±(99.9%) 0.683 ms/op
                 createUser·p0.00:   7.365 ms/op
                 createUser·p0.50:   17.039 ms/op
                 createUser·p0.90:   32.552 ms/op
                 createUser·p0.95:   38.722 ms/op
                 createUser·p0.99:   45.482 ms/op
                 createUser·p0.999:  68.298 ms/op
                 createUser·p0.9999: 68.551 ms/op
                 createUser·p1.00:   68.551 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 1642
  mean =     19.159 ±(99.9%) 0.683 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 46 
    [10.000, 15.000) = 624 
    [15.000, 20.000) = 388 
    [20.000, 25.000) = 327 
    [25.000, 30.000) = 78 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 96 
    [40.000, 45.000) = 30 
    [45.000, 50.000) = 17 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      7.365 ms/op
     p(50.0000) =     17.039 ms/op
     p(90.0000) =     32.552 ms/op
     p(95.0000) =     38.722 ms/op
     p(99.0000) =     45.482 ms/op
     p(99.9000) =     68.298 ms/op
     p(99.9900) =     68.551 ms/op
     p(99.9990) =     68.551 ms/op
     p(99.9999) =     68.551 ms/op
    p(100.0000) =     68.551 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:25
# Fork: 1 of 1
# Warmup Iteration   1: 24.191 ±(99.9%) 0.988 ms/op
Iteration   1: 11.911 ±(99.9%) 0.336 ms/op
                 existUser·p0.00:   2.032 ms/op
                 existUser·p0.50:   11.092 ms/op
                 existUser·p0.90:   18.026 ms/op
                 existUser·p0.95:   21.529 ms/op
                 existUser·p0.99:   38.949 ms/op
                 existUser·p0.999:  41.222 ms/op
                 existUser·p0.9999: 41.353 ms/op
                 existUser·p1.00:   41.353 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 2668
  mean =     11.911 ±(99.9%) 0.336 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 98 
    [ 5.000, 10.000) = 910 
    [10.000, 15.000) = 1169 
    [15.000, 20.000) = 299 
    [20.000, 25.000) = 151 
    [25.000, 30.000) = 9 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =     11.092 ms/op
     p(90.0000) =     18.026 ms/op
     p(95.0000) =     21.529 ms/op
     p(99.0000) =     38.949 ms/op
     p(99.9000) =     41.222 ms/op
     p(99.9900) =     41.353 ms/op
     p(99.9990) =     41.353 ms/op
     p(99.9999) =     41.353 ms/op
    p(100.0000) =     41.353 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:17
# Fork: 1 of 1
# Warmup Iteration   1: 25.843 ±(99.9%) 1.395 ms/op
Iteration   1: 15.853 ±(99.9%) 0.561 ms/op
                 getUser·p0.00:   5.603 ms/op
                 getUser·p0.50:   13.550 ms/op
                 getUser·p0.90:   26.771 ms/op
                 getUser·p0.95:   30.291 ms/op
                 getUser·p0.99:   44.045 ms/op
                 getUser·p0.999:  45.352 ms/op
                 getUser·p0.9999: 45.548 ms/op
                 getUser·p1.00:   45.548 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 1991
  mean =     15.853 ±(99.9%) 0.561 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 387 
    [10.000, 15.000) = 835 
    [15.000, 20.000) = 308 
    [20.000, 25.000) = 186 
    [25.000, 30.000) = 164 
    [30.000, 35.000) = 50 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 35 

  Percentiles, ms/op:
      p(0.0000) =      5.603 ms/op
     p(50.0000) =     13.550 ms/op
     p(90.0000) =     26.771 ms/op
     p(95.0000) =     30.291 ms/op
     p(99.0000) =     44.045 ms/op
     p(99.9000) =     45.352 ms/op
     p(99.9900) =     45.548 ms/op
     p(99.9990) =     45.548 ms/op
     p(99.9999) =     45.548 ms/op
    p(100.0000) =     45.548 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:08
# Fork: 1 of 1
# Warmup Iteration   1: 47.642 ±(99.9%) 3.422 ms/op
Iteration   1: 35.000 ±(99.9%) 1.018 ms/op
                 listUser·p0.00:   18.481 ms/op
                 listUser·p0.50:   32.948 ms/op
                 listUser·p0.90:   47.402 ms/op
                 listUser·p0.95:   52.101 ms/op
                 listUser·p0.99:   64.447 ms/op
                 listUser·p0.999:  89.522 ms/op
                 listUser·p0.9999: 89.522 ms/op
                 listUser·p1.00:   89.522 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 886
  mean =     35.000 ±(99.9%) 1.018 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 33 
    [25.000, 30.000) = 287 
    [30.000, 35.000) = 237 
    [35.000, 40.000) = 140 
    [40.000, 45.000) = 63 
    [45.000, 50.000) = 54 
    [50.000, 55.000) = 34 
    [55.000, 60.000) = 7 
    [60.000, 65.000) = 21 
    [65.000, 70.000) = 6 
    [70.000, 75.000) = 0 
    [75.000, 80.000) = 0 
    [80.000, 85.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =     18.481 ms/op
     p(50.0000) =     32.948 ms/op
     p(90.0000) =     47.402 ms/op
     p(95.0000) =     52.101 ms/op
     p(99.0000) =     64.447 ms/op
     p(99.9000) =     89.522 ms/op
     p(99.9900) =     89.522 ms/op
     p(99.9990) =     89.522 ms/op
     p(99.9999) =     89.522 ms/op
    p(100.0000) =     89.522 ms/op


# Run complete. Total time: 00:01:42

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         0.718          ops/ms
Client.existUser                       thrpt         2.187          ops/ms
Client.getUser                         thrpt         1.711          ops/ms
Client.listUser                        thrpt         0.624          ops/ms
Client.createUser                       avgt        27.537           ms/op
Client.existUser                        avgt        13.498           ms/op
Client.getUser                          avgt        15.740           ms/op
Client.listUser                         avgt        40.761           ms/op
Client.createUser                     sample  1642  19.159 ± 0.683   ms/op
Client.createUser:createUser·p0.00    sample         7.365           ms/op
Client.createUser:createUser·p0.50    sample        17.039           ms/op
Client.createUser:createUser·p0.90    sample        32.552           ms/op
Client.createUser:createUser·p0.95    sample        38.722           ms/op
Client.createUser:createUser·p0.99    sample        45.482           ms/op
Client.createUser:createUser·p0.999   sample        68.298           ms/op
Client.createUser:createUser·p0.9999  sample        68.551           ms/op
Client.createUser:createUser·p1.00    sample        68.551           ms/op
Client.existUser                      sample  2668  11.911 ± 0.336   ms/op
Client.existUser:existUser·p0.00      sample         2.032           ms/op
Client.existUser:existUser·p0.50      sample        11.092           ms/op
Client.existUser:existUser·p0.90      sample        18.026           ms/op
Client.existUser:existUser·p0.95      sample        21.529           ms/op
Client.existUser:existUser·p0.99      sample        38.949           ms/op
Client.existUser:existUser·p0.999     sample        41.222           ms/op
Client.existUser:existUser·p0.9999    sample        41.353           ms/op
Client.existUser:existUser·p1.00      sample        41.353           ms/op
Client.getUser                        sample  1991  15.853 ± 0.561   ms/op
Client.getUser:getUser·p0.00          sample         5.603           ms/op
Client.getUser:getUser·p0.50          sample        13.550           ms/op
Client.getUser:getUser·p0.90          sample        26.771           ms/op
Client.getUser:getUser·p0.95          sample        30.291           ms/op
Client.getUser:getUser·p0.99          sample        44.045           ms/op
Client.getUser:getUser·p0.999         sample        45.352           ms/op
Client.getUser:getUser·p0.9999        sample        45.548           ms/op
Client.getUser:getUser·p1.00          sample        45.548           ms/op
Client.listUser                       sample   886  35.000 ± 1.018   ms/op
Client.listUser:listUser·p0.00        sample        18.481           ms/op
Client.listUser:listUser·p0.50        sample        32.948           ms/op
Client.listUser:listUser·p0.90        sample        47.402           ms/op
Client.listUser:listUser·p0.95        sample        52.101           ms/op
Client.listUser:listUser·p0.99        sample        64.447           ms/op
Client.listUser:listUser·p0.999       sample        89.522           ms/op
Client.listUser:listUser·p0.9999      sample        89.522           ms/op
Client.listUser:listUser·p1.00        sample        89.522           ms/op
