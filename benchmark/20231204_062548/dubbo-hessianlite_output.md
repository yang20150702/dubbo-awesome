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
# Warmup Iteration   1: 2.100 ops/ms
Iteration   1: 5.432 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.432 ops/ms


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
# Warmup Iteration   1: 6.086 ops/ms
Iteration   1: 12.549 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.549 ops/ms


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
# Warmup Iteration   1: 3.947 ops/ms
Iteration   1: 8.491 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.491 ops/ms


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
# Warmup Iteration   1: 1.994 ops/ms
Iteration   1: 3.089 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.089 ops/ms


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
# Warmup Iteration   1: 5.721 ±(99.9%) 0.079 ms/op
Iteration   1: 3.010 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.010 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.032 ms/op
Iteration   1: 1.892 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.892 ms/op


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
# Warmup Iteration   1: 5.769 ±(99.9%) 0.066 ms/op
Iteration   1: 3.000 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.000 ms/op


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
# Warmup Iteration   1: 11.797 ±(99.9%) 0.237 ms/op
Iteration   1: 9.466 ±(99.9%) 0.169 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.466 ms/op


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
# Warmup Iteration   1: 4.791 ±(99.9%) 0.096 ms/op
Iteration   1: 3.053 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.446 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  13.255 ms/op
                 createUser·p0.9999: 13.564 ms/op
                 createUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10485
  mean =      3.053 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2930 
    [ 2.500,  3.750) = 6217 
    [ 3.750,  5.000) = 1103 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.446 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     13.564 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


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
# Warmup Iteration   1: 3.535 ±(99.9%) 0.110 ms/op
Iteration   1: 1.858 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.448 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.384 ms/op
                 existUser·p0.99:   2.923 ms/op
                 existUser·p0.999:  6.390 ms/op
                 existUser·p0.9999: 6.859 ms/op
                 existUser·p1.00:   6.865 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17217
  mean =      1.858 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 8 
    [1.000, 1.500) = 935 
    [1.500, 2.000) = 12726 
    [2.000, 2.500) = 2988 
    [2.500, 3.000) = 416 
    [3.000, 3.500) = 63 
    [3.500, 4.000) = 38 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 0 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.384 ms/op
     p(99.0000) =      2.923 ms/op
     p(99.9000) =      6.390 ms/op
     p(99.9900) =      6.859 ms/op
     p(99.9990) =      6.865 ms/op
     p(99.9999) =      6.865 ms/op
    p(100.0000) =      6.865 ms/op


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
# Warmup Iteration   1: 4.886 ±(99.9%) 0.127 ms/op
Iteration   1: 3.161 ±(99.9%) 0.100 ms/op
                 getUser·p0.00:   0.499 ms/op
                 getUser·p0.50:   2.777 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.412 ms/op
                 getUser·p0.99:   7.914 ms/op
                 getUser·p0.999:  59.117 ms/op
                 getUser·p0.9999: 75.869 ms/op
                 getUser·p1.00:   76.284 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10448
  mean =      3.161 ±(99.9%) 0.100 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10131 
    [ 5.000, 10.000) = 229 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 5 
    [70.000, 75.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.412 ms/op
     p(99.0000) =      7.914 ms/op
     p(99.9000) =     59.117 ms/op
     p(99.9900) =     75.869 ms/op
     p(99.9990) =     76.284 ms/op
     p(99.9999) =     76.284 ms/op
    p(100.0000) =     76.284 ms/op


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
# Warmup Iteration   1: 16.483 ±(99.9%) 0.863 ms/op
Iteration   1: 8.402 ±(99.9%) 0.179 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   7.832 ms/op
                 listUser·p0.90:   10.863 ms/op
                 listUser·p0.95:   12.137 ms/op
                 listUser·p0.99:   19.306 ms/op
                 listUser·p0.999:  49.137 ms/op
                 listUser·p0.9999: 70.910 ms/op
                 listUser·p1.00:   70.910 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3783
  mean =      8.402 ±(99.9%) 0.179 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 93 
    [ 5.000, 10.000) = 3092 
    [10.000, 15.000) = 530 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 11 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      7.832 ms/op
     p(90.0000) =     10.863 ms/op
     p(95.0000) =     12.137 ms/op
     p(99.0000) =     19.306 ms/op
     p(99.9000) =     49.137 ms/op
     p(99.9900) =     70.910 ms/op
     p(99.9990) =     70.910 ms/op
     p(99.9999) =     70.910 ms/op
    p(100.0000) =     70.910 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.432          ops/ms
Client.existUser                       thrpt         12.549          ops/ms
Client.getUser                         thrpt          8.491          ops/ms
Client.listUser                        thrpt          3.089          ops/ms
Client.createUser                       avgt          3.010           ms/op
Client.existUser                        avgt          1.892           ms/op
Client.getUser                          avgt          3.000           ms/op
Client.listUser                         avgt          9.466           ms/op
Client.createUser                     sample  10485   3.053 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.325           ms/op
Client.createUser:createUser·p0.50    sample          2.818           ms/op
Client.createUser:createUser·p0.90    sample          3.932           ms/op
Client.createUser:createUser·p0.95    sample          4.446           ms/op
Client.createUser:createUser·p0.99    sample          9.519           ms/op
Client.createUser:createUser·p0.999   sample         13.255           ms/op
Client.createUser:createUser·p0.9999  sample         13.564           ms/op
Client.createUser:createUser·p1.00    sample         13.566           ms/op
Client.existUser                      sample  17217   1.858 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.448           ms/op
Client.existUser:existUser·p0.50      sample          1.810           ms/op
Client.existUser:existUser·p0.90      sample          2.183           ms/op
Client.existUser:existUser·p0.95      sample          2.384           ms/op
Client.existUser:existUser·p0.99      sample          2.923           ms/op
Client.existUser:existUser·p0.999     sample          6.390           ms/op
Client.existUser:existUser·p0.9999    sample          6.859           ms/op
Client.existUser:existUser·p1.00      sample          6.865           ms/op
Client.getUser                        sample  10448   3.161 ± 0.100   ms/op
Client.getUser:getUser·p0.00          sample          0.499           ms/op
Client.getUser:getUser·p0.50          sample          2.777           ms/op
Client.getUser:getUser·p0.90          sample          3.777           ms/op
Client.getUser:getUser·p0.95          sample          4.412           ms/op
Client.getUser:getUser·p0.99          sample          7.914           ms/op
Client.getUser:getUser·p0.999         sample         59.117           ms/op
Client.getUser:getUser·p0.9999        sample         75.869           ms/op
Client.getUser:getUser·p1.00          sample         76.284           ms/op
Client.listUser                       sample   3783   8.402 ± 0.179   ms/op
Client.listUser:listUser·p0.00        sample          2.228           ms/op
Client.listUser:listUser·p0.50        sample          7.832           ms/op
Client.listUser:listUser·p0.90        sample         10.863           ms/op
Client.listUser:listUser·p0.95        sample         12.137           ms/op
Client.listUser:listUser·p0.99        sample         19.306           ms/op
Client.listUser:listUser·p0.999       sample         49.137           ms/op
Client.listUser:listUser·p0.9999      sample         70.910           ms/op
Client.listUser:listUser·p1.00        sample         70.910           ms/op
