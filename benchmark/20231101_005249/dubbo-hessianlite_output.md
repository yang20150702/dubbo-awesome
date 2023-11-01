# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.734 ops/ms
Iteration   1: 4.484 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.484 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.422 ops/ms
Iteration   1: 9.634 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.634 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 2.733 ops/ms
Iteration   1: 6.439 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.439 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.257 ops/ms
Iteration   1: 1.581 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.581 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 10.388 ±(99.9%) 0.191 ms/op
Iteration   1: 4.505 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.505 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.025 ±(99.9%) 0.080 ms/op
Iteration   1: 2.256 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.256 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.775 ±(99.9%) 0.129 ms/op
Iteration   1: 3.946 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.946 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 28.390 ±(99.9%) 0.711 ms/op
Iteration   1: 15.503 ±(99.9%) 0.235 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.503 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.787 ±(99.9%) 0.264 ms/op
Iteration   1: 3.896 ±(99.9%) 0.132 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   8.503 ms/op
                 createUser·p0.99:   14.811 ms/op
                 createUser·p0.999:  53.084 ms/op
                 createUser·p0.9999: 55.706 ms/op
                 createUser·p1.00:   55.706 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8450
  mean =      3.896 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7125 
    [ 5.000, 10.000) = 1038 
    [10.000, 15.000) = 207 
    [15.000, 20.000) = 48 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     14.811 ms/op
     p(99.9000) =     53.084 ms/op
     p(99.9900) =     55.706 ms/op
     p(99.9990) =     55.706 ms/op
     p(99.9999) =     55.706 ms/op
    p(100.0000) =     55.706 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.470 ±(99.9%) 0.138 ms/op
Iteration   1: 2.138 ±(99.9%) 0.055 ms/op
                 existUser·p0.00:   0.269 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   3.085 ms/op
                 existUser·p0.99:   10.807 ms/op
                 existUser·p0.999:  34.542 ms/op
                 existUser·p0.9999: 48.050 ms/op
                 existUser·p1.00:   51.642 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14937
  mean =      2.138 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14482 
    [ 5.000, 10.000) = 287 
    [10.000, 15.000) = 120 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.269 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      3.085 ms/op
     p(99.0000) =     10.807 ms/op
     p(99.9000) =     34.542 ms/op
     p(99.9900) =     48.050 ms/op
     p(99.9990) =     51.642 ms/op
     p(99.9999) =     51.642 ms/op
    p(100.0000) =     51.642 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.262 ms/op
Iteration   1: 3.297 ±(99.9%) 0.083 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.630 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   6.631 ms/op
                 getUser·p0.99:   13.645 ms/op
                 getUser·p0.999:  26.875 ms/op
                 getUser·p0.9999: 28.410 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9834
  mean =      3.297 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3576 
    [ 2.500,  5.000) = 5368 
    [ 5.000,  7.500) = 610 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      6.631 ms/op
     p(99.0000) =     13.645 ms/op
     p(99.9000) =     26.875 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.790 ±(99.9%) 0.972 ms/op
Iteration   1: 16.717 ±(99.9%) 0.289 ms/op
                 listUser·p0.00:   8.520 ms/op
                 listUser·p0.50:   16.130 ms/op
                 listUser·p0.90:   22.118 ms/op
                 listUser·p0.95:   24.707 ms/op
                 listUser·p0.99:   27.591 ms/op
                 listUser·p0.999:  36.604 ms/op
                 listUser·p0.9999: 37.880 ms/op
                 listUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1926
  mean =     16.717 ±(99.9%) 0.289 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 481 
    [15.000, 17.500) = 642 
    [17.500, 20.000) = 312 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      8.520 ms/op
     p(50.0000) =     16.130 ms/op
     p(90.0000) =     22.118 ms/op
     p(95.0000) =     24.707 ms/op
     p(99.0000) =     27.591 ms/op
     p(99.9000) =     36.604 ms/op
     p(99.9900) =     37.880 ms/op
     p(99.9990) =     37.880 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.484          ops/ms
Client.existUser                       thrpt          9.634          ops/ms
Client.getUser                         thrpt          6.439          ops/ms
Client.listUser                        thrpt          1.581          ops/ms
Client.createUser                       avgt          4.505           ms/op
Client.existUser                        avgt          2.256           ms/op
Client.getUser                          avgt          3.946           ms/op
Client.listUser                         avgt         15.503           ms/op
Client.createUser                     sample   8450   3.896 ± 0.132   ms/op
Client.createUser:createUser·p0.00    sample          1.292           ms/op
Client.createUser:createUser·p0.50    sample          2.966           ms/op
Client.createUser:createUser·p0.90    sample          6.267           ms/op
Client.createUser:createUser·p0.95    sample          8.503           ms/op
Client.createUser:createUser·p0.99    sample         14.811           ms/op
Client.createUser:createUser·p0.999   sample         53.084           ms/op
Client.createUser:createUser·p0.9999  sample         55.706           ms/op
Client.createUser:createUser·p1.00    sample         55.706           ms/op
Client.existUser                      sample  14937   2.138 ± 0.055   ms/op
Client.existUser:existUser·p0.00      sample          0.269           ms/op
Client.existUser:existUser·p0.50      sample          1.829           ms/op
Client.existUser:existUser·p0.90      sample          2.400           ms/op
Client.existUser:existUser·p0.95      sample          3.085           ms/op
Client.existUser:existUser·p0.99      sample         10.807           ms/op
Client.existUser:existUser·p0.999     sample         34.542           ms/op
Client.existUser:existUser·p0.9999    sample         48.050           ms/op
Client.existUser:existUser·p1.00      sample         51.642           ms/op
Client.getUser                        sample   9834   3.297 ± 0.083   ms/op
Client.getUser:getUser·p0.00          sample          0.997           ms/op
Client.getUser:getUser·p0.50          sample          2.630           ms/op
Client.getUser:getUser·p0.90          sample          4.620           ms/op
Client.getUser:getUser·p0.95          sample          6.631           ms/op
Client.getUser:getUser·p0.99          sample         13.645           ms/op
Client.getUser:getUser·p0.999         sample         26.875           ms/op
Client.getUser:getUser·p0.9999        sample         28.410           ms/op
Client.getUser:getUser·p1.00          sample         28.410           ms/op
Client.listUser                       sample   1926  16.717 ± 0.289   ms/op
Client.listUser:listUser·p0.00        sample          8.520           ms/op
Client.listUser:listUser·p0.50        sample         16.130           ms/op
Client.listUser:listUser·p0.90        sample         22.118           ms/op
Client.listUser:listUser·p0.95        sample         24.707           ms/op
Client.listUser:listUser·p0.99        sample         27.591           ms/op
Client.listUser:listUser·p0.999       sample         36.604           ms/op
Client.listUser:listUser·p0.9999      sample         37.880           ms/op
Client.listUser:listUser·p1.00        sample         37.880           ms/op
