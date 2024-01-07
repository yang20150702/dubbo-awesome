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
# Warmup Iteration   1: 2.126 ops/ms
Iteration   1: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.812 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.295 ops/ms
Iteration   1: 11.847 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.847 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.590 ops/ms
Iteration   1: 8.898 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.898 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.052 ops/ms
Iteration   1: 3.381 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.381 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.743 ±(99.9%) 0.083 ms/op
Iteration   1: 3.055 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.055 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.015 ±(99.9%) 0.033 ms/op
Iteration   1: 1.858 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.858 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.925 ±(99.9%) 0.071 ms/op
Iteration   1: 2.957 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.957 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.652 ±(99.9%) 0.280 ms/op
Iteration   1: 8.707 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.707 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.894 ±(99.9%) 0.108 ms/op
Iteration   1: 3.103 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   7.416 ms/op
                 createUser·p0.999:  14.590 ms/op
                 createUser·p0.9999: 14.794 ms/op
                 createUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10367
  mean =      3.103 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2040 
    [ 2.500,  3.750) = 7266 
    [ 3.750,  5.000) = 741 
    [ 5.000,  6.250) = 174 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.416 ms/op
     p(99.9000) =     14.590 ms/op
     p(99.9900) =     14.794 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.092 ±(99.9%) 0.062 ms/op
Iteration   1: 1.855 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.298 ms/op
                 existUser·p0.99:   2.748 ms/op
                 existUser·p0.999:  11.305 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17341
  mean =      1.855 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 240 
    [ 1.250,  2.500) = 16678 
    [ 2.500,  3.750) = 353 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.298 ms/op
     p(99.0000) =      2.748 ms/op
     p(99.9000) =     11.305 ms/op
     p(99.9900) =     11.862 ms/op
     p(99.9990) =     11.862 ms/op
     p(99.9999) =     11.862 ms/op
    p(100.0000) =     11.862 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 5.453 ±(99.9%) 0.298 ms/op
Iteration   1: 3.024 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   2.834 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  8.575 ms/op
                 getUser·p0.9999: 9.739 ms/op
                 getUser·p1.00:   9.798 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10599
  mean =      3.024 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 5 
    [ 1.500,  2.000) = 205 
    [ 2.000,  2.500) = 2721 
    [ 2.500,  3.000) = 2915 
    [ 3.000,  3.500) = 2297 
    [ 3.500,  4.000) = 1668 
    [ 4.000,  4.500) = 441 
    [ 4.500,  5.000) = 158 
    [ 5.000,  5.500) = 48 
    [ 5.500,  6.000) = 17 
    [ 6.000,  6.500) = 27 
    [ 6.500,  7.000) = 32 
    [ 7.000,  7.500) = 8 
    [ 7.500,  8.000) = 22 
    [ 8.000,  8.500) = 22 
    [ 8.500,  9.000) = 12 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =      8.575 ms/op
     p(99.9900) =      9.739 ms/op
     p(99.9990) =      9.798 ms/op
     p(99.9999) =      9.798 ms/op
    p(100.0000) =      9.798 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.426 ±(99.9%) 0.553 ms/op
Iteration   1: 8.690 ±(99.9%) 0.132 ms/op
                 listUser·p0.00:   2.990 ms/op
                 listUser·p0.50:   8.298 ms/op
                 listUser·p0.90:   11.485 ms/op
                 listUser·p0.95:   12.882 ms/op
                 listUser·p0.99:   16.908 ms/op
                 listUser·p0.999:  30.304 ms/op
                 listUser·p0.9999: 31.621 ms/op
                 listUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3694
  mean =      8.690 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 75 
    [ 5.000,  7.500) = 1047 
    [ 7.500, 10.000) = 1818 
    [10.000, 12.500) = 518 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.990 ms/op
     p(50.0000) =      8.298 ms/op
     p(90.0000) =     11.485 ms/op
     p(95.0000) =     12.882 ms/op
     p(99.0000) =     16.908 ms/op
     p(99.9000) =     30.304 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.812          ops/ms
Client.existUser                       thrpt         11.847          ops/ms
Client.getUser                         thrpt          8.898          ops/ms
Client.listUser                        thrpt          3.381          ops/ms
Client.createUser                       avgt          3.055           ms/op
Client.existUser                        avgt          1.858           ms/op
Client.getUser                          avgt          2.957           ms/op
Client.listUser                         avgt          8.707           ms/op
Client.createUser                     sample  10367   3.103 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.272           ms/op
Client.createUser:createUser·p0.50    sample          2.908           ms/op
Client.createUser:createUser·p0.90    sample          3.781           ms/op
Client.createUser:createUser·p0.95    sample          4.448           ms/op
Client.createUser:createUser·p0.99    sample          7.416           ms/op
Client.createUser:createUser·p0.999   sample         14.590           ms/op
Client.createUser:createUser·p0.9999  sample         14.794           ms/op
Client.createUser:createUser·p1.00    sample         14.795           ms/op
Client.existUser                      sample  17341   1.855 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.612           ms/op
Client.existUser:existUser·p0.50      sample          1.804           ms/op
Client.existUser:existUser·p0.90      sample          2.138           ms/op
Client.existUser:existUser·p0.95      sample          2.298           ms/op
Client.existUser:existUser·p0.99      sample          2.748           ms/op
Client.existUser:existUser·p0.999     sample         11.305           ms/op
Client.existUser:existUser·p0.9999    sample         11.862           ms/op
Client.existUser:existUser·p1.00      sample         11.862           ms/op
Client.getUser                        sample  10599   3.024 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          1.403           ms/op
Client.getUser:getUser·p0.50          sample          2.834           ms/op
Client.getUser:getUser·p0.90          sample          3.863           ms/op
Client.getUser:getUser·p0.95          sample          4.186           ms/op
Client.getUser:getUser·p0.99          sample          6.201           ms/op
Client.getUser:getUser·p0.999         sample          8.575           ms/op
Client.getUser:getUser·p0.9999        sample          9.739           ms/op
Client.getUser:getUser·p1.00          sample          9.798           ms/op
Client.listUser                       sample   3694   8.690 ± 0.132   ms/op
Client.listUser:listUser·p0.00        sample          2.990           ms/op
Client.listUser:listUser·p0.50        sample          8.298           ms/op
Client.listUser:listUser·p0.90        sample         11.485           ms/op
Client.listUser:listUser·p0.95        sample         12.882           ms/op
Client.listUser:listUser·p0.99        sample         16.908           ms/op
Client.listUser:listUser·p0.999       sample         30.304           ms/op
Client.listUser:listUser·p0.9999      sample         31.621           ms/op
Client.listUser:listUser·p1.00        sample         31.621           ms/op
