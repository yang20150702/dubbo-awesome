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
# Warmup Iteration   1: 2.611 ops/ms
Iteration   1: 5.920 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.920 ops/ms


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
# Warmup Iteration   1: 5.549 ops/ms
Iteration   1: 12.979 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.979 ops/ms


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
# Warmup Iteration   1: 4.262 ops/ms
Iteration   1: 9.904 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.904 ops/ms


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
# Warmup Iteration   1: 2.366 ops/ms
Iteration   1: 3.830 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.830 ops/ms


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
# Warmup Iteration   1: 5.487 ±(99.9%) 0.089 ms/op
Iteration   1: 3.407 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.407 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.027 ms/op
Iteration   1: 1.922 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.922 ms/op


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.051 ms/op
Iteration   1: 2.945 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.945 ms/op


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
# Warmup Iteration   1: 11.217 ±(99.9%) 0.136 ms/op
Iteration   1: 7.276 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.276 ms/op


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.129 ms/op
Iteration   1: 2.963 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   2.810 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 10.174 ms/op
                 createUser·p1.00:   10.174 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10791
  mean =      2.963 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 81 
    [ 2.000,  3.000) = 7632 
    [ 3.000,  4.000) = 2525 
    [ 4.000,  5.000) = 281 
    [ 5.000,  6.000) = 47 
    [ 6.000,  7.000) = 97 
    [ 7.000,  8.000) = 64 
    [ 8.000,  9.000) = 18 
    [ 9.000, 10.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     10.125 ms/op
     p(99.9900) =     10.174 ms/op
     p(99.9990) =     10.174 ms/op
     p(99.9999) =     10.174 ms/op
    p(100.0000) =     10.174 ms/op


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
# Warmup Iteration   1: 2.774 ±(99.9%) 0.072 ms/op
Iteration   1: 2.032 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   1.921 ms/op
                 existUser·p0.90:   2.720 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  5.895 ms/op
                 existUser·p0.9999: 7.478 ms/op
                 existUser·p1.00:   7.487 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15794
  mean =      2.032 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 11 
    [1.000, 1.500) = 1643 
    [1.500, 2.000) = 7316 
    [2.000, 2.500) = 4251 
    [2.500, 3.000) = 1904 
    [3.000, 3.500) = 490 
    [3.500, 4.000) = 43 
    [4.000, 4.500) = 10 
    [4.500, 5.000) = 47 
    [5.000, 5.500) = 40 
    [5.500, 6.000) = 24 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 10 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      5.895 ms/op
     p(99.9900) =      7.478 ms/op
     p(99.9990) =      7.487 ms/op
     p(99.9999) =      7.487 ms/op
    p(100.0000) =      7.487 ms/op


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.097 ms/op
Iteration   1: 3.092 ±(99.9%) 0.062 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   2.748 ms/op
                 getUser·p0.90:   3.987 ms/op
                 getUser·p0.95:   4.499 ms/op
                 getUser·p0.99:   7.282 ms/op
                 getUser·p0.999:  23.843 ms/op
                 getUser·p0.9999: 28.100 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10355
  mean =      3.092 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3592 
    [ 2.500,  5.000) = 6483 
    [ 5.000,  7.500) = 179 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      3.987 ms/op
     p(95.0000) =      4.499 ms/op
     p(99.0000) =      7.282 ms/op
     p(99.9000) =     23.843 ms/op
     p(99.9900) =     28.100 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 12.775 ±(99.9%) 0.417 ms/op
Iteration   1: 7.508 ±(99.9%) 0.126 ms/op
                 listUser·p0.00:   3.129 ms/op
                 listUser·p0.50:   7.168 ms/op
                 listUser·p0.90:   9.732 ms/op
                 listUser·p0.95:   10.797 ms/op
                 listUser·p0.99:   16.400 ms/op
                 listUser·p0.999:  28.703 ms/op
                 listUser·p0.9999: 29.655 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4265
  mean =      7.508 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 253 
    [ 5.000,  7.500) = 2262 
    [ 7.500, 10.000) = 1396 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      3.129 ms/op
     p(50.0000) =      7.168 ms/op
     p(90.0000) =      9.732 ms/op
     p(95.0000) =     10.797 ms/op
     p(99.0000) =     16.400 ms/op
     p(99.9000) =     28.703 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     29.655 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.920          ops/ms
Client.existUser                       thrpt         12.979          ops/ms
Client.getUser                         thrpt          9.904          ops/ms
Client.listUser                        thrpt          3.830          ops/ms
Client.createUser                       avgt          3.407           ms/op
Client.existUser                        avgt          1.922           ms/op
Client.getUser                          avgt          2.945           ms/op
Client.listUser                         avgt          7.276           ms/op
Client.createUser                     sample  10791   2.963 ± 0.026   ms/op
Client.createUser:createUser·p0.00    sample          1.231           ms/op
Client.createUser:createUser·p0.50    sample          2.810           ms/op
Client.createUser:createUser·p0.90    sample          3.527           ms/op
Client.createUser:createUser·p0.95    sample          4.006           ms/op
Client.createUser:createUser·p0.99    sample          7.143           ms/op
Client.createUser:createUser·p0.999   sample         10.125           ms/op
Client.createUser:createUser·p0.9999  sample         10.174           ms/op
Client.createUser:createUser·p1.00    sample         10.174           ms/op
Client.existUser                      sample  15794   2.032 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.766           ms/op
Client.existUser:existUser·p0.50      sample          1.921           ms/op
Client.existUser:existUser·p0.90      sample          2.720           ms/op
Client.existUser:existUser·p0.95      sample          2.961           ms/op
Client.existUser:existUser·p0.99      sample          3.645           ms/op
Client.existUser:existUser·p0.999     sample          5.895           ms/op
Client.existUser:existUser·p0.9999    sample          7.478           ms/op
Client.existUser:existUser·p1.00      sample          7.487           ms/op
Client.getUser                        sample  10355   3.092 ± 0.062   ms/op
Client.getUser:getUser·p0.00          sample          1.180           ms/op
Client.getUser:getUser·p0.50          sample          2.748           ms/op
Client.getUser:getUser·p0.90          sample          3.987           ms/op
Client.getUser:getUser·p0.95          sample          4.499           ms/op
Client.getUser:getUser·p0.99          sample          7.282           ms/op
Client.getUser:getUser·p0.999         sample         23.843           ms/op
Client.getUser:getUser·p0.9999        sample         28.100           ms/op
Client.getUser:getUser·p1.00          sample         28.246           ms/op
Client.listUser                       sample   4265   7.508 ± 0.126   ms/op
Client.listUser:listUser·p0.00        sample          3.129           ms/op
Client.listUser:listUser·p0.50        sample          7.168           ms/op
Client.listUser:listUser·p0.90        sample          9.732           ms/op
Client.listUser:listUser·p0.95        sample         10.797           ms/op
Client.listUser:listUser·p0.99        sample         16.400           ms/op
Client.listUser:listUser·p0.999       sample         28.703           ms/op
Client.listUser:listUser·p0.9999      sample         29.655           ms/op
Client.listUser:listUser·p1.00        sample         29.655           ms/op
