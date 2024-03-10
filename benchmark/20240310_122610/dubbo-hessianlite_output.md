# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.609 ops/ms
Iteration   1: 6.393 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.393 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.889 ops/ms
Iteration   1: 13.158 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.158 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.547 ops/ms
Iteration   1: 9.635 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.635 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.124 ops/ms
Iteration   1: 3.863 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.863 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.676 ±(99.9%) 0.077 ms/op
Iteration   1: 3.338 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.338 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.378 ±(99.9%) 0.037 ms/op
Iteration   1: 1.861 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.861 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.812 ±(99.9%) 0.071 ms/op
Iteration   1: 3.052 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.052 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.235 ±(99.9%) 0.185 ms/op
Iteration   1: 8.753 ±(99.9%) 0.134 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.973 ±(99.9%) 0.100 ms/op
Iteration   1: 3.979 ±(99.9%) 0.147 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.673 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   16.593 ms/op
                 createUser·p0.999:  62.585 ms/op
                 createUser·p0.9999: 63.177 ms/op
                 createUser·p1.00:   63.177 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8025
  mean =      3.979 ±(99.9%) 0.147 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7443 
    [ 5.000, 10.000) = 454 
    [10.000, 15.000) = 33 
    [15.000, 20.000) = 63 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.673 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =     16.593 ms/op
     p(99.9000) =     62.585 ms/op
     p(99.9900) =     63.177 ms/op
     p(99.9990) =     63.177 ms/op
     p(99.9999) =     63.177 ms/op
    p(100.0000) =     63.177 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.262 ±(99.9%) 0.118 ms/op
Iteration   1: 1.852 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.888 ms/op
                 existUser·p0.99:   3.507 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 13.706 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17270
  mean =      1.852 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1595 
    [ 1.250,  2.500) = 13621 
    [ 2.500,  3.750) = 1935 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      3.507 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     13.706 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.326 ±(99.9%) 0.112 ms/op
Iteration   1: 3.202 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   7.596 ms/op
                 getUser·p0.999:  11.795 ms/op
                 getUser·p0.9999: 13.042 ms/op
                 getUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10023
  mean =      3.202 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1722 
    [ 2.500,  3.750) = 6414 
    [ 3.750,  5.000) = 1555 
    [ 5.000,  6.250) = 157 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.596 ms/op
     p(99.9000) =     11.795 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.042 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.946 ±(99.9%) 0.372 ms/op
Iteration   1: 7.974 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   7.651 ms/op
                 listUser·p0.90:   10.404 ms/op
                 listUser·p0.95:   11.436 ms/op
                 listUser·p0.99:   16.416 ms/op
                 listUser·p0.999:  22.739 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4017
  mean =      7.974 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 106 
    [ 5.000,  7.500) = 1766 
    [ 7.500, 10.000) = 1625 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      7.651 ms/op
     p(90.0000) =     10.404 ms/op
     p(95.0000) =     11.436 ms/op
     p(99.0000) =     16.416 ms/op
     p(99.9000) =     22.739 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.393          ops/ms
Client.existUser                       thrpt         13.158          ops/ms
Client.getUser                         thrpt          9.635          ops/ms
Client.listUser                        thrpt          3.863          ops/ms
Client.createUser                       avgt          3.338           ms/op
Client.existUser                        avgt          1.861           ms/op
Client.getUser                          avgt          3.052           ms/op
Client.listUser                         avgt          8.753           ms/op
Client.createUser                     sample   8025   3.979 ± 0.147   ms/op
Client.createUser:createUser·p0.00    sample          0.786           ms/op
Client.createUser:createUser·p0.50    sample          3.490           ms/op
Client.createUser:createUser·p0.90    sample          4.673           ms/op
Client.createUser:createUser·p0.95    sample          5.407           ms/op
Client.createUser:createUser·p0.99    sample         16.593           ms/op
Client.createUser:createUser·p0.999   sample         62.585           ms/op
Client.createUser:createUser·p0.9999  sample         63.177           ms/op
Client.createUser:createUser·p1.00    sample         63.177           ms/op
Client.existUser                      sample  17270   1.852 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.582           ms/op
Client.existUser:existUser·p0.50      sample          1.726           ms/op
Client.existUser:existUser·p0.90      sample          2.601           ms/op
Client.existUser:existUser·p0.95      sample          2.888           ms/op
Client.existUser:existUser·p0.99      sample          3.507           ms/op
Client.existUser:existUser·p0.999     sample         13.042           ms/op
Client.existUser:existUser·p0.9999    sample         13.706           ms/op
Client.existUser:existUser·p1.00      sample         13.730           ms/op
Client.getUser                        sample  10023   3.202 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.734           ms/op
Client.getUser:getUser·p0.50          sample          3.052           ms/op
Client.getUser:getUser·p0.90          sample          4.035           ms/op
Client.getUser:getUser·p0.95          sample          4.563           ms/op
Client.getUser:getUser·p0.99          sample          7.596           ms/op
Client.getUser:getUser·p0.999         sample         11.795           ms/op
Client.getUser:getUser·p0.9999        sample         13.042           ms/op
Client.getUser:getUser·p1.00          sample         13.042           ms/op
Client.listUser                       sample   4017   7.974 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          1.544           ms/op
Client.listUser:listUser·p0.50        sample          7.651           ms/op
Client.listUser:listUser·p0.90        sample         10.404           ms/op
Client.listUser:listUser·p0.95        sample         11.436           ms/op
Client.listUser:listUser·p0.99        sample         16.416           ms/op
Client.listUser:listUser·p0.999       sample         22.739           ms/op
Client.listUser:listUser·p0.9999      sample         24.183           ms/op
Client.listUser:listUser·p1.00        sample         24.183           ms/op
