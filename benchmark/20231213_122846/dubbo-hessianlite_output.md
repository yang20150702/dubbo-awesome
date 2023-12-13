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
# Warmup Iteration   1: 2.369 ops/ms
Iteration   1: 6.128 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.128 ops/ms


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
# Warmup Iteration   1: 6.282 ops/ms
Iteration   1: 13.968 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.968 ops/ms


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
# Warmup Iteration   1: 3.635 ops/ms
Iteration   1: 8.498 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.498 ops/ms


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
# Warmup Iteration   1: 2.134 ops/ms
Iteration   1: 3.249 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.249 ops/ms


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
# Warmup Iteration   1: 4.769 ±(99.9%) 0.097 ms/op
Iteration   1: 3.289 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.289 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.030 ms/op
Iteration   1: 1.878 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.878 ms/op


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
# Warmup Iteration   1: 4.506 ±(99.9%) 0.048 ms/op
Iteration   1: 3.304 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.304 ms/op


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
# Warmup Iteration   1: 12.965 ±(99.9%) 0.232 ms/op
Iteration   1: 8.456 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.456 ms/op


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.109 ms/op
Iteration   1: 2.929 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   2.785 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.786 ms/op
                 createUser·p0.99:   6.972 ms/op
                 createUser·p0.999:  11.745 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10893
  mean =      2.929 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1628 
    [ 2.500,  3.750) = 8699 
    [ 3.750,  5.000) = 351 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.786 ms/op
     p(99.0000) =      6.972 ms/op
     p(99.9000) =     11.745 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.128 ms/op
Iteration   1: 1.937 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.222 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.631 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  20.611 ms/op
                 existUser·p0.9999: 21.104 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16573
  mean =      1.937 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15133 
    [ 2.500,  5.000) = 1376 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.222 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.631 ms/op
     p(99.0000) =      3.437 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     21.104 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.934 ±(99.9%) 0.121 ms/op
Iteration   1: 3.081 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 9.657 ms/op
                 getUser·p1.00:   9.667 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10348
  mean =      3.081 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 37 
    [ 1.000,  2.000) = 360 
    [ 2.000,  3.000) = 4780 
    [ 3.000,  4.000) = 4189 
    [ 4.000,  5.000) = 777 
    [ 5.000,  6.000) = 130 
    [ 6.000,  7.000) = 36 
    [ 7.000,  8.000) = 21 
    [ 8.000,  9.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =      9.657 ms/op
     p(99.9990) =      9.667 ms/op
     p(99.9999) =      9.667 ms/op
    p(100.0000) =      9.667 ms/op


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
# Warmup Iteration   1: 13.140 ±(99.9%) 0.489 ms/op
Iteration   1: 8.367 ±(99.9%) 0.155 ms/op
                 listUser·p0.00:   2.884 ms/op
                 listUser·p0.50:   7.963 ms/op
                 listUser·p0.90:   10.584 ms/op
                 listUser·p0.95:   11.567 ms/op
                 listUser·p0.99:   16.136 ms/op
                 listUser·p0.999:  37.966 ms/op
                 listUser·p0.9999: 40.370 ms/op
                 listUser·p1.00:   40.370 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3806
  mean =      8.367 ±(99.9%) 0.155 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 56 
    [ 5.000, 10.000) = 3183 
    [10.000, 15.000) = 522 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.884 ms/op
     p(50.0000) =      7.963 ms/op
     p(90.0000) =     10.584 ms/op
     p(95.0000) =     11.567 ms/op
     p(99.0000) =     16.136 ms/op
     p(99.9000) =     37.966 ms/op
     p(99.9900) =     40.370 ms/op
     p(99.9990) =     40.370 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.128          ops/ms
Client.existUser                       thrpt         13.968          ops/ms
Client.getUser                         thrpt          8.498          ops/ms
Client.listUser                        thrpt          3.249          ops/ms
Client.createUser                       avgt          3.289           ms/op
Client.existUser                        avgt          1.878           ms/op
Client.getUser                          avgt          3.304           ms/op
Client.listUser                         avgt          8.456           ms/op
Client.createUser                     sample  10893   2.929 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.231           ms/op
Client.createUser:createUser·p0.50    sample          2.785           ms/op
Client.createUser:createUser·p0.90    sample          3.404           ms/op
Client.createUser:createUser·p0.95    sample          3.786           ms/op
Client.createUser:createUser·p0.99    sample          6.972           ms/op
Client.createUser:createUser·p0.999   sample         11.745           ms/op
Client.createUser:createUser·p0.9999  sample         13.894           ms/op
Client.createUser:createUser·p1.00    sample         13.894           ms/op
Client.existUser                      sample  16573   1.937 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.222           ms/op
Client.existUser:existUser·p0.50      sample          1.890           ms/op
Client.existUser:existUser·p0.90      sample          2.466           ms/op
Client.existUser:existUser·p0.95      sample          2.631           ms/op
Client.existUser:existUser·p0.99      sample          3.437           ms/op
Client.existUser:existUser·p0.999     sample         20.611           ms/op
Client.existUser:existUser·p0.9999    sample         21.104           ms/op
Client.existUser:existUser·p1.00      sample         21.168           ms/op
Client.getUser                        sample  10348   3.081 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.563           ms/op
Client.getUser:getUser·p0.50          sample          2.998           ms/op
Client.getUser:getUser·p0.90          sample          3.965           ms/op
Client.getUser:getUser·p0.95          sample          4.350           ms/op
Client.getUser:getUser·p0.99          sample          5.685           ms/op
Client.getUser:getUser·p0.999         sample          9.290           ms/op
Client.getUser:getUser·p0.9999        sample          9.657           ms/op
Client.getUser:getUser·p1.00          sample          9.667           ms/op
Client.listUser                       sample   3806   8.367 ± 0.155   ms/op
Client.listUser:listUser·p0.00        sample          2.884           ms/op
Client.listUser:listUser·p0.50        sample          7.963           ms/op
Client.listUser:listUser·p0.90        sample         10.584           ms/op
Client.listUser:listUser·p0.95        sample         11.567           ms/op
Client.listUser:listUser·p0.99        sample         16.136           ms/op
Client.listUser:listUser·p0.999       sample         37.966           ms/op
Client.listUser:listUser·p0.9999      sample         40.370           ms/op
Client.listUser:listUser·p1.00        sample         40.370           ms/op
