# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
Iteration   1: 7.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.041 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.401 ops/ms
Iteration   1: 13.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.426 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ops/ms
Iteration   1: 13.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.687 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ops/ms
Iteration   1: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.343 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ±(99.9%) 0.077 ms/op
Iteration   1: 2.149 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.208 ±(99.9%) 0.054 ms/op
Iteration   1: 1.909 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.909 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ±(99.9%) 0.074 ms/op
Iteration   1: 1.978 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.978 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ±(99.9%) 0.073 ms/op
Iteration   1: 3.340 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.340 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.520 ±(99.9%) 0.119 ms/op
Iteration   1: 2.152 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   1.948 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.847 ms/op
                 createUser·p0.99:   8.102 ms/op
                 createUser·p0.999:  30.020 ms/op
                 createUser·p0.9999: 30.657 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14861
  mean =      2.152 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13090 
    [ 2.500,  5.000) = 1494 
    [ 5.000,  7.500) = 88 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     30.020 ms/op
     p(99.9900) =     30.657 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.450 ±(99.9%) 0.092 ms/op
Iteration   1: 1.787 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   1.659 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.425 ms/op
                 existUser·p0.99:   3.019 ms/op
                 existUser·p0.999:  13.096 ms/op
                 existUser·p0.9999: 14.508 ms/op
                 existUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17918
  mean =      1.787 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 528 
    [ 1.250,  2.500) = 16737 
    [ 2.500,  3.750) = 549 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.425 ms/op
     p(99.0000) =      3.019 ms/op
     p(99.9000) =     13.096 ms/op
     p(99.9900) =     14.508 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.325 ±(99.9%) 0.100 ms/op
Iteration   1: 1.904 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.505 ms/op
                 getUser·p0.50:   1.780 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   3.261 ms/op
                 getUser·p0.999:  13.746 ms/op
                 getUser·p0.9999: 14.150 ms/op
                 getUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16797
  mean =      1.904 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 15457 
    [ 2.500,  3.750) = 1145 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.261 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     14.150 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.205 ±(99.9%) 0.131 ms/op
Iteration   1: 3.143 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.806 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.986 ms/op
                 listUser·p0.999:  22.184 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10232
  mean =      3.143 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2501 
    [ 2.500,  5.000) = 7439 
    [ 5.000,  7.500) = 224 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.986 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.041          ops/ms
ClientSimple.existUser                       thrpt         13.426          ops/ms
ClientSimple.getUser                         thrpt         13.687          ops/ms
ClientSimple.listUser                        thrpt          8.343          ops/ms
ClientSimple.createUser                       avgt          2.149           ms/op
ClientSimple.existUser                        avgt          1.909           ms/op
ClientSimple.getUser                          avgt          1.978           ms/op
ClientSimple.listUser                         avgt          3.340           ms/op
ClientSimple.createUser                     sample  14861   2.152 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.616           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.948           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.102           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.020           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.657           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.736           ms/op
ClientSimple.existUser                      sample  17918   1.787 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.787           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.659           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.019           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.096           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.508           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.664           ms/op
ClientSimple.getUser                        sample  16797   1.904 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.505           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.780           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.261           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.746           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.150           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.172           ms/op
ClientSimple.listUser                       sample  10232   3.143 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.920           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.806           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.957           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.986           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.184           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.576           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.576           ms/op

Benchmark result is saved to 1723529676542.json
