# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.889 ops/ms
Iteration   1: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.910 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.323 ops/ms
Iteration   1: 12.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.747 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.702 ops/ms
Iteration   1: 14.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.180 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.138 ops/ms
Iteration   1: 7.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.988 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ±(99.9%) 0.068 ms/op
Iteration   1: 1.976 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.976 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.205 ±(99.9%) 0.060 ms/op
Iteration   1: 1.742 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.742 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.355 ±(99.9%) 0.058 ms/op
Iteration   1: 1.918 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ±(99.9%) 0.088 ms/op
Iteration   1: 3.460 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ±(99.9%) 0.093 ms/op
Iteration   1: 1.957 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.370 ms/op
                 createUser·p0.50:   1.792 ms/op
                 createUser·p0.90:   2.257 ms/op
                 createUser·p0.95:   2.494 ms/op
                 createUser·p0.99:   8.096 ms/op
                 createUser·p0.999:  11.409 ms/op
                 createUser·p0.9999: 13.976 ms/op
                 createUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16328
  mean =      1.957 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 15362 
    [ 2.500,  3.750) = 548 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      8.096 ms/op
     p(99.9000) =     11.409 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.946 ±(99.9%) 0.063 ms/op
Iteration   1: 2.012 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   1.896 ms/op
                 existUser·p0.90:   2.472 ms/op
                 existUser·p0.95:   2.646 ms/op
                 existUser·p0.99:   3.444 ms/op
                 existUser·p0.999:  23.832 ms/op
                 existUser·p0.9999: 24.329 ms/op
                 existUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15903
  mean =      2.012 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14475 
    [ 2.500,  5.000) = 1280 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.472 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.444 ms/op
     p(99.9000) =     23.832 ms/op
     p(99.9900) =     24.329 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.235 ±(99.9%) 0.073 ms/op
Iteration   1: 1.908 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   1.624 ms/op
                 getUser·p0.90:   2.691 ms/op
                 getUser·p0.95:   2.896 ms/op
                 getUser·p0.99:   3.437 ms/op
                 getUser·p0.999:  13.918 ms/op
                 getUser·p0.9999: 14.677 ms/op
                 getUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17066
  mean =      1.908 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 407 
    [ 1.250,  2.500) = 13813 
    [ 2.500,  3.750) = 2740 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      1.624 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      3.437 ms/op
     p(99.9000) =     13.918 ms/op
     p(99.9900) =     14.677 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.124 ms/op
Iteration   1: 3.405 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.391 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  8.086 ms/op
                 listUser·p0.9999: 8.184 ms/op
                 listUser·p1.00:   8.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9391
  mean =      3.405 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 24 
    [1.500, 2.000) = 45 
    [2.000, 2.500) = 505 
    [2.500, 3.000) = 2178 
    [3.000, 3.500) = 2713 
    [3.500, 4.000) = 2512 
    [4.000, 4.500) = 1048 
    [4.500, 5.000) = 172 
    [5.000, 5.500) = 39 
    [5.500, 6.000) = 80 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 35 
    [7.500, 8.000) = 12 
    [8.000, 8.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =      8.184 ms/op
     p(99.9990) =      8.184 ms/op
     p(99.9999) =      8.184 ms/op
    p(100.0000) =      8.184 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.910          ops/ms
ClientSimple.existUser                       thrpt         12.747          ops/ms
ClientSimple.getUser                         thrpt         14.180          ops/ms
ClientSimple.listUser                        thrpt          7.988          ops/ms
ClientSimple.createUser                       avgt          1.976           ms/op
ClientSimple.existUser                        avgt          1.742           ms/op
ClientSimple.getUser                          avgt          1.918           ms/op
ClientSimple.listUser                         avgt          3.460           ms/op
ClientSimple.createUser                     sample  16328   1.957 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.370           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.792           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.257           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.494           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.096           ms/op
ClientSimple.createUser:createUser·p0.999   sample         11.409           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.976           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.976           ms/op
ClientSimple.existUser                      sample  15903   2.012 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.660           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.896           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.472           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.444           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.832           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.329           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.445           ms/op
ClientSimple.getUser                        sample  17066   1.908 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.677           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.624           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.437           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.918           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.677           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.221           ms/op
ClientSimple.listUser                       sample   9391   3.405 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.212           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.391           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.800           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.086           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.184           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.184           ms/op

Benchmark result is saved to 1718584955912.json
