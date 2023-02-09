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
# Warmup Iteration   1: 0.364 ops/ms
Iteration   1: 0.937 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  0.937 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:29
# Fork: 1 of 1
# Warmup Iteration   1: 1.246 ops/ms
Iteration   1: 3.503 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.503 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 0.807 ops/ms
Iteration   1: 1.811 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  1.811 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 0.538 ops/ms
Iteration   1: 0.662 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.662 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 33.368 ±(99.9%) 0.672 ms/op
Iteration   1: 21.641 ±(99.9%) 0.263 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  21.641 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 25.861 ±(99.9%) 0.378 ms/op
Iteration   1: 11.924 ±(99.9%) 0.061 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.924 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 32.875 ±(99.9%) 0.656 ms/op
Iteration   1: 14.128 ±(99.9%) 0.192 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  14.128 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:40
# Fork: 1 of 1
# Warmup Iteration   1: 67.251 ±(99.9%) 2.622 ms/op
Iteration   1: 35.813 ±(99.9%) 0.426 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  35.813 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:32
# Fork: 1 of 1
# Warmup Iteration   1: 25.029 ±(99.9%) 1.023 ms/op
Iteration   1: 14.396 ±(99.9%) 0.433 ms/op
                 createUser·p0.00:   5.226 ms/op
                 createUser·p0.50:   12.845 ms/op
                 createUser·p0.90:   22.941 ms/op
                 createUser·p0.95:   28.213 ms/op
                 createUser·p0.99:   39.387 ms/op
                 createUser·p0.999:  46.455 ms/op
                 createUser·p0.9999: 48.759 ms/op
                 createUser·p1.00:   48.759 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2202
  mean =     14.396 ±(99.9%) 0.433 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 296 
    [10.000, 15.000) = 1323 
    [15.000, 20.000) = 297 
    [20.000, 25.000) = 115 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 53 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      5.226 ms/op
     p(50.0000) =     12.845 ms/op
     p(90.0000) =     22.941 ms/op
     p(95.0000) =     28.213 ms/op
     p(99.0000) =     39.387 ms/op
     p(99.9000) =     46.455 ms/op
     p(99.9900) =     48.759 ms/op
     p(99.9990) =     48.759 ms/op
     p(99.9999) =     48.759 ms/op
    p(100.0000) =     48.759 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 19.568 ±(99.9%) 0.619 ms/op
Iteration   1: 10.038 ±(99.9%) 0.276 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   9.814 ms/op
                 existUser·p0.90:   15.024 ms/op
                 existUser·p0.95:   17.724 ms/op
                 existUser·p0.99:   30.343 ms/op
                 existUser·p0.999:  34.931 ms/op
                 existUser·p0.9999: 34.996 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3190
  mean =     10.038 ±(99.9%) 0.276 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 244 
    [ 5.000,  7.500) = 765 
    [ 7.500, 10.000) = 656 
    [10.000, 12.500) = 913 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      9.814 ms/op
     p(90.0000) =     15.024 ms/op
     p(95.0000) =     17.724 ms/op
     p(99.0000) =     30.343 ms/op
     p(99.9000) =     34.931 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:16
# Fork: 1 of 1
# Warmup Iteration   1: 18.313 ±(99.9%) 0.796 ms/op
Iteration   1: 10.941 ±(99.9%) 0.291 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   10.125 ms/op
                 getUser·p0.90:   14.728 ms/op
                 getUser·p0.95:   17.236 ms/op
                 getUser·p0.99:   39.332 ms/op
                 getUser·p0.999:  44.504 ms/op
                 getUser·p0.9999: 45.548 ms/op
                 getUser·p1.00:   45.548 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 2920
  mean =     10.941 ±(99.9%) 0.291 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 54 
    [ 5.000, 10.000) = 1306 
    [10.000, 15.000) = 1293 
    [15.000, 20.000) = 166 
    [20.000, 25.000) = 52 
    [25.000, 30.000) = 10 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =     10.125 ms/op
     p(90.0000) =     14.728 ms/op
     p(95.0000) =     17.236 ms/op
     p(99.0000) =     39.332 ms/op
     p(99.9000) =     44.504 ms/op
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
# Warmup Iteration   1: 41.683 ±(99.9%) 1.918 ms/op
Iteration   1: 27.032 ±(99.9%) 0.728 ms/op
                 listUser·p0.00:   10.011 ms/op
                 listUser·p0.50:   25.690 ms/op
                 listUser·p0.90:   33.125 ms/op
                 listUser·p0.95:   37.634 ms/op
                 listUser·p0.99:   65.482 ms/op
                 listUser·p0.999:  75.982 ms/op
                 listUser·p0.9999: 76.677 ms/op
                 listUser·p1.00:   76.677 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1182
  mean =     27.032 ±(99.9%) 0.728 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 18 
    [15.000, 20.000) = 64 
    [20.000, 25.000) = 385 
    [25.000, 30.000) = 528 
    [30.000, 35.000) = 107 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 14 
    [50.000, 55.000) = 6 
    [55.000, 60.000) = 8 
    [60.000, 65.000) = 5 
    [65.000, 70.000) = 11 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =     10.011 ms/op
     p(50.0000) =     25.690 ms/op
     p(90.0000) =     33.125 ms/op
     p(95.0000) =     37.634 ms/op
     p(99.0000) =     65.482 ms/op
     p(99.9000) =     75.982 ms/op
     p(99.9900) =     76.677 ms/op
     p(99.9990) =     76.677 ms/op
     p(99.9999) =     76.677 ms/op
    p(100.0000) =     76.677 ms/op


# Run complete. Total time: 00:01:38

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         0.937          ops/ms
Client.existUser                       thrpt         3.503          ops/ms
Client.getUser                         thrpt         1.811          ops/ms
Client.listUser                        thrpt         0.662          ops/ms
Client.createUser                       avgt        21.641           ms/op
Client.existUser                        avgt        11.924           ms/op
Client.getUser                          avgt        14.128           ms/op
Client.listUser                         avgt        35.813           ms/op
Client.createUser                     sample  2202  14.396 ± 0.433   ms/op
Client.createUser:createUser·p0.00    sample         5.226           ms/op
Client.createUser:createUser·p0.50    sample        12.845           ms/op
Client.createUser:createUser·p0.90    sample        22.941           ms/op
Client.createUser:createUser·p0.95    sample        28.213           ms/op
Client.createUser:createUser·p0.99    sample        39.387           ms/op
Client.createUser:createUser·p0.999   sample        46.455           ms/op
Client.createUser:createUser·p0.9999  sample        48.759           ms/op
Client.createUser:createUser·p1.00    sample        48.759           ms/op
Client.existUser                      sample  3190  10.038 ± 0.276   ms/op
Client.existUser:existUser·p0.00      sample         1.403           ms/op
Client.existUser:existUser·p0.50      sample         9.814           ms/op
Client.existUser:existUser·p0.90      sample        15.024           ms/op
Client.existUser:existUser·p0.95      sample        17.724           ms/op
Client.existUser:existUser·p0.99      sample        30.343           ms/op
Client.existUser:existUser·p0.999     sample        34.931           ms/op
Client.existUser:existUser·p0.9999    sample        34.996           ms/op
Client.existUser:existUser·p1.00      sample        34.996           ms/op
Client.getUser                        sample  2920  10.941 ± 0.291   ms/op
Client.getUser:getUser·p0.00          sample         1.745           ms/op
Client.getUser:getUser·p0.50          sample        10.125           ms/op
Client.getUser:getUser·p0.90          sample        14.728           ms/op
Client.getUser:getUser·p0.95          sample        17.236           ms/op
Client.getUser:getUser·p0.99          sample        39.332           ms/op
Client.getUser:getUser·p0.999         sample        44.504           ms/op
Client.getUser:getUser·p0.9999        sample        45.548           ms/op
Client.getUser:getUser·p1.00          sample        45.548           ms/op
Client.listUser                       sample  1182  27.032 ± 0.728   ms/op
Client.listUser:listUser·p0.00        sample        10.011           ms/op
Client.listUser:listUser·p0.50        sample        25.690           ms/op
Client.listUser:listUser·p0.90        sample        33.125           ms/op
Client.listUser:listUser·p0.95        sample        37.634           ms/op
Client.listUser:listUser·p0.99        sample        65.482           ms/op
Client.listUser:listUser·p0.999       sample        75.982           ms/op
Client.listUser:listUser·p0.9999      sample        76.677           ms/op
Client.listUser:listUser·p1.00        sample        76.677           ms/op
