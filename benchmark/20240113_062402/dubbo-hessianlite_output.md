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
# Warmup Iteration   1: 2.084 ops/ms
Iteration   1: 5.597 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.597 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.879 ops/ms
Iteration   1: 12.763 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.763 ops/ms


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
# Warmup Iteration   1: 4.530 ops/ms
Iteration   1: 8.310 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.310 ops/ms


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
# Warmup Iteration   1: 2.221 ops/ms
Iteration   1: 3.735 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.735 ops/ms


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
# Warmup Iteration   1: 5.246 ±(99.9%) 0.068 ms/op
Iteration   1: 3.155 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.155 ms/op


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
# Warmup Iteration   1: 3.015 ±(99.9%) 0.032 ms/op
Iteration   1: 1.815 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.815 ms/op


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.047 ms/op
Iteration   1: 2.929 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.929 ms/op


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
# Warmup Iteration   1: 12.468 ±(99.9%) 0.227 ms/op
Iteration   1: 8.608 ±(99.9%) 0.117 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.608 ms/op


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
# Warmup Iteration   1: 5.030 ±(99.9%) 0.108 ms/op
Iteration   1: 3.051 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.871 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.239 ms/op
                 createUser·p0.99:   8.303 ms/op
                 createUser·p0.999:  12.665 ms/op
                 createUser·p0.9999: 12.871 ms/op
                 createUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10850
  mean =      3.051 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 2630 
    [ 2.500,  3.750) = 6805 
    [ 3.750,  5.000) = 1126 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.239 ms/op
     p(99.0000) =      8.303 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     12.871 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 2.943 ±(99.9%) 0.057 ms/op
Iteration   1: 1.776 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.487 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   2.179 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.273 ms/op
                 existUser·p0.999:  25.919 ms/op
                 existUser·p0.9999: 26.365 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18045
  mean =      1.776 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17210 
    [ 2.500,  5.000) = 753 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.273 ms/op
     p(99.9000) =     25.919 ms/op
     p(99.9900) =     26.365 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.099 ms/op
Iteration   1: 3.028 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   2.753 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  11.312 ms/op
                 getUser·p0.9999: 11.485 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10550
  mean =      3.028 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1849 
    [ 2.500,  3.750) = 6964 
    [ 3.750,  5.000) = 1543 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     11.312 ms/op
     p(99.9900) =     11.485 ms/op
     p(99.9990) =     11.485 ms/op
     p(99.9999) =     11.485 ms/op
    p(100.0000) =     11.485 ms/op


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
# Warmup Iteration   1: 12.179 ±(99.9%) 0.430 ms/op
Iteration   1: 9.401 ±(99.9%) 0.160 ms/op
                 listUser·p0.00:   3.363 ms/op
                 listUser·p0.50:   8.995 ms/op
                 listUser·p0.90:   12.868 ms/op
                 listUser·p0.95:   14.077 ms/op
                 listUser·p0.99:   21.335 ms/op
                 listUser·p0.999:  28.228 ms/op
                 listUser·p0.9999: 28.901 ms/op
                 listUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3395
  mean =      9.401 ±(99.9%) 0.160 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 69 
    [ 5.000,  7.500) = 726 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 807 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      3.363 ms/op
     p(50.0000) =      8.995 ms/op
     p(90.0000) =     12.868 ms/op
     p(95.0000) =     14.077 ms/op
     p(99.0000) =     21.335 ms/op
     p(99.9000) =     28.228 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.597          ops/ms
Client.existUser                       thrpt         12.763          ops/ms
Client.getUser                         thrpt          8.310          ops/ms
Client.listUser                        thrpt          3.735          ops/ms
Client.createUser                       avgt          3.155           ms/op
Client.existUser                        avgt          1.815           ms/op
Client.getUser                          avgt          2.929           ms/op
Client.listUser                         avgt          8.608           ms/op
Client.createUser                     sample  10850   3.051 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          0.926           ms/op
Client.createUser:createUser·p0.50    sample          2.871           ms/op
Client.createUser:createUser·p0.90    sample          3.883           ms/op
Client.createUser:createUser·p0.95    sample          4.239           ms/op
Client.createUser:createUser·p0.99    sample          8.303           ms/op
Client.createUser:createUser·p0.999   sample         12.665           ms/op
Client.createUser:createUser·p0.9999  sample         12.871           ms/op
Client.createUser:createUser·p1.00    sample         12.878           ms/op
Client.existUser                      sample  18045   1.776 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.487           ms/op
Client.existUser:existUser·p0.50      sample          1.632           ms/op
Client.existUser:existUser·p0.90      sample          2.179           ms/op
Client.existUser:existUser·p0.95      sample          2.474           ms/op
Client.existUser:existUser·p0.99      sample          3.273           ms/op
Client.existUser:existUser·p0.999     sample         25.919           ms/op
Client.existUser:existUser·p0.9999    sample         26.365           ms/op
Client.existUser:existUser·p1.00      sample         26.444           ms/op
Client.getUser                        sample  10550   3.028 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          0.570           ms/op
Client.getUser:getUser·p0.50          sample          2.753           ms/op
Client.getUser:getUser·p0.90          sample          4.014           ms/op
Client.getUser:getUser·p0.95          sample          4.473           ms/op
Client.getUser:getUser·p0.99          sample          6.382           ms/op
Client.getUser:getUser·p0.999         sample         11.312           ms/op
Client.getUser:getUser·p0.9999        sample         11.485           ms/op
Client.getUser:getUser·p1.00          sample         11.485           ms/op
Client.listUser                       sample   3395   9.401 ± 0.160   ms/op
Client.listUser:listUser·p0.00        sample          3.363           ms/op
Client.listUser:listUser·p0.50        sample          8.995           ms/op
Client.listUser:listUser·p0.90        sample         12.868           ms/op
Client.listUser:listUser·p0.95        sample         14.077           ms/op
Client.listUser:listUser·p0.99        sample         21.335           ms/op
Client.listUser:listUser·p0.999       sample         28.228           ms/op
Client.listUser:listUser·p0.9999      sample         28.901           ms/op
Client.listUser:listUser·p1.00        sample         28.901           ms/op
