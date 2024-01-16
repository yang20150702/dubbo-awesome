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
# Warmup Iteration   1: 1.859 ops/ms
Iteration   1: 5.242 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.242 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ops/ms
Iteration   1: 11.764 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.764 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.498 ops/ms
Iteration   1: 7.575 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.575 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.075 ops/ms
Iteration   1: 3.715 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.715 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.579 ±(99.9%) 0.075 ms/op
Iteration   1: 3.243 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.243 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.340 ±(99.9%) 0.044 ms/op
Iteration   1: 1.876 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.876 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.309 ±(99.9%) 0.063 ms/op
Iteration   1: 2.962 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.962 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.580 ±(99.9%) 0.179 ms/op
Iteration   1: 8.482 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.482 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.421 ±(99.9%) 0.171 ms/op
Iteration   1: 3.111 ±(99.9%) 0.072 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   2.834 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   10.120 ms/op
                 createUser·p0.999:  38.470 ms/op
                 createUser·p0.9999: 40.632 ms/op
                 createUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10366
  mean =      3.111 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10007 
    [ 5.000, 10.000) = 255 
    [10.000, 15.000) = 72 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =     10.120 ms/op
     p(99.9000) =     38.470 ms/op
     p(99.9900) =     40.632 ms/op
     p(99.9990) =     40.632 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.050 ±(99.9%) 0.069 ms/op
Iteration   1: 1.867 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   1.731 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   2.963 ms/op
                 existUser·p0.999:  21.457 ms/op
                 existUser·p0.9999: 22.885 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17171
  mean =      1.867 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16157 
    [ 2.500,  5.000) = 943 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      2.963 ms/op
     p(99.9000) =     21.457 ms/op
     p(99.9900) =     22.885 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 5.154 ±(99.9%) 0.226 ms/op
Iteration   1: 3.136 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  18.394 ms/op
                 getUser·p0.9999: 20.766 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10316
  mean =      3.136 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2548 
    [ 2.500,  5.000) = 7542 
    [ 5.000,  7.500) = 148 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     18.394 ms/op
     p(99.9900) =     20.766 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 13.139 ±(99.9%) 0.481 ms/op
Iteration   1: 7.369 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   6.971 ms/op
                 listUser·p0.90:   9.617 ms/op
                 listUser·p0.95:   10.666 ms/op
                 listUser·p0.99:   18.645 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 23.986 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4335
  mean =      7.369 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 308 
    [ 5.000,  7.500) = 2365 
    [ 7.500, 10.000) = 1331 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      6.971 ms/op
     p(90.0000) =      9.617 ms/op
     p(95.0000) =     10.666 ms/op
     p(99.0000) =     18.645 ms/op
     p(99.9000) =     23.462 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.242          ops/ms
Client.existUser                       thrpt         11.764          ops/ms
Client.getUser                         thrpt          7.575          ops/ms
Client.listUser                        thrpt          3.715          ops/ms
Client.createUser                       avgt          3.243           ms/op
Client.existUser                        avgt          1.876           ms/op
Client.getUser                          avgt          2.962           ms/op
Client.listUser                         avgt          8.482           ms/op
Client.createUser                     sample  10366   3.111 ± 0.072   ms/op
Client.createUser:createUser·p0.00    sample          0.762           ms/op
Client.createUser:createUser·p0.50    sample          2.834           ms/op
Client.createUser:createUser·p0.90    sample          3.498           ms/op
Client.createUser:createUser·p0.95    sample          4.399           ms/op
Client.createUser:createUser·p0.99    sample         10.120           ms/op
Client.createUser:createUser·p0.999   sample         38.470           ms/op
Client.createUser:createUser·p0.9999  sample         40.632           ms/op
Client.createUser:createUser·p1.00    sample         40.632           ms/op
Client.existUser                      sample  17171   1.867 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.535           ms/op
Client.existUser:existUser·p0.50      sample          1.731           ms/op
Client.existUser:existUser·p0.90      sample          2.372           ms/op
Client.existUser:existUser·p0.95      sample          2.544           ms/op
Client.existUser:existUser·p0.99      sample          2.963           ms/op
Client.existUser:existUser·p0.999     sample         21.457           ms/op
Client.existUser:existUser·p0.9999    sample         22.885           ms/op
Client.existUser:existUser·p1.00      sample         23.167           ms/op
Client.getUser                        sample  10316   3.136 ± 0.042   ms/op
Client.getUser:getUser·p0.00          sample          0.893           ms/op
Client.getUser:getUser·p0.50          sample          3.002           ms/op
Client.getUser:getUser·p0.90          sample          3.990           ms/op
Client.getUser:getUser·p0.95          sample          4.293           ms/op
Client.getUser:getUser·p0.99          sample          7.127           ms/op
Client.getUser:getUser·p0.999         sample         18.394           ms/op
Client.getUser:getUser·p0.9999        sample         20.766           ms/op
Client.getUser:getUser·p1.00          sample         20.775           ms/op
Client.listUser                       sample   4335   7.369 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          1.475           ms/op
Client.listUser:listUser·p0.50        sample          6.971           ms/op
Client.listUser:listUser·p0.90        sample          9.617           ms/op
Client.listUser:listUser·p0.95        sample         10.666           ms/op
Client.listUser:listUser·p0.99        sample         18.645           ms/op
Client.listUser:listUser·p0.999       sample         23.462           ms/op
Client.listUser:listUser·p0.9999      sample         23.986           ms/op
Client.listUser:listUser·p1.00        sample         23.986           ms/op
