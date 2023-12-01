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
# Warmup Iteration   1: 2.191 ops/ms
Iteration   1: 6.240 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.240 ops/ms


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
# Warmup Iteration   1: 5.941 ops/ms
Iteration   1: 13.296 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.296 ops/ms


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
# Warmup Iteration   1: 4.051 ops/ms
Iteration   1: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.493 ops/ms


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
# Warmup Iteration   1: 2.222 ops/ms
Iteration   1: 3.624 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.624 ops/ms


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
# Warmup Iteration   1: 5.393 ±(99.9%) 0.073 ms/op
Iteration   1: 3.066 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.066 ms/op


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
# Warmup Iteration   1: 3.268 ±(99.9%) 0.031 ms/op
Iteration   1: 1.879 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.879 ms/op


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.058 ms/op
Iteration   1: 3.094 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.094 ms/op


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
# Warmup Iteration   1: 12.042 ±(99.9%) 0.212 ms/op
Iteration   1: 8.042 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.042 ms/op


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
# Warmup Iteration   1: 4.730 ±(99.9%) 0.093 ms/op
Iteration   1: 2.867 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.221 ms/op
                 createUser·p0.99:   6.225 ms/op
                 createUser·p0.999:  12.204 ms/op
                 createUser·p0.9999: 12.319 ms/op
                 createUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11155
  mean =      2.867 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 3331 
    [ 2.500,  3.750) = 6723 
    [ 3.750,  5.000) = 860 
    [ 5.000,  6.250) = 120 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.221 ms/op
     p(99.0000) =      6.225 ms/op
     p(99.9000) =     12.204 ms/op
     p(99.9900) =     12.319 ms/op
     p(99.9990) =     12.321 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


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
# Warmup Iteration   1: 3.332 ±(99.9%) 0.082 ms/op
Iteration   1: 1.812 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   1.743 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.261 ms/op
                 existUser·p0.99:   2.890 ms/op
                 existUser·p0.999:  26.533 ms/op
                 existUser·p0.9999: 27.857 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17631
  mean =      1.812 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17217 
    [ 2.500,  5.000) = 356 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.261 ms/op
     p(99.0000) =      2.890 ms/op
     p(99.9000) =     26.533 ms/op
     p(99.9900) =     27.857 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 4.210 ±(99.9%) 0.094 ms/op
Iteration   1: 3.059 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.845 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  8.611 ms/op
                 getUser·p0.9999: 8.909 ms/op
                 getUser·p1.00:   8.913 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10451
  mean =      3.059 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 11 
    [1.000, 1.500) = 52 
    [1.500, 2.000) = 309 
    [2.000, 2.500) = 1314 
    [2.500, 3.000) = 3970 
    [3.000, 3.500) = 2674 
    [3.500, 4.000) = 1414 
    [4.000, 4.500) = 379 
    [4.500, 5.000) = 125 
    [5.000, 5.500) = 72 
    [5.500, 6.000) = 55 
    [6.000, 6.500) = 16 
    [6.500, 7.000) = 10 
    [7.000, 7.500) = 14 
    [7.500, 8.000) = 5 
    [8.000, 8.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.845 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      8.611 ms/op
     p(99.9900) =      8.909 ms/op
     p(99.9990) =      8.913 ms/op
     p(99.9999) =      8.913 ms/op
    p(100.0000) =      8.913 ms/op


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
# Warmup Iteration   1: 11.580 ±(99.9%) 0.433 ms/op
Iteration   1: 7.372 ±(99.9%) 0.087 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   7.168 ms/op
                 listUser·p0.90:   9.159 ms/op
                 listUser·p0.95:   10.019 ms/op
                 listUser·p0.99:   12.599 ms/op
                 listUser·p0.999:  19.399 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4329
  mean =      7.372 ±(99.9%) 0.087 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 14 
    [ 3.750,  5.000) = 130 
    [ 5.000,  6.250) = 853 
    [ 6.250,  7.500) = 1569 
    [ 7.500,  8.750) = 1168 
    [ 8.750, 10.000) = 374 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.396 ms/op
     p(50.0000) =      7.168 ms/op
     p(90.0000) =      9.159 ms/op
     p(95.0000) =     10.019 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.240          ops/ms
Client.existUser                       thrpt         13.296          ops/ms
Client.getUser                         thrpt          8.493          ops/ms
Client.listUser                        thrpt          3.624          ops/ms
Client.createUser                       avgt          3.066           ms/op
Client.existUser                        avgt          1.879           ms/op
Client.getUser                          avgt          3.094           ms/op
Client.listUser                         avgt          8.042           ms/op
Client.createUser                     sample  11155   2.867 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          0.784           ms/op
Client.createUser:createUser·p0.50    sample          2.634           ms/op
Client.createUser:createUser·p0.90    sample          3.678           ms/op
Client.createUser:createUser·p0.95    sample          4.221           ms/op
Client.createUser:createUser·p0.99    sample          6.225           ms/op
Client.createUser:createUser·p0.999   sample         12.204           ms/op
Client.createUser:createUser·p0.9999  sample         12.319           ms/op
Client.createUser:createUser·p1.00    sample         12.321           ms/op
Client.existUser                      sample  17631   1.812 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.532           ms/op
Client.existUser:existUser·p0.50      sample          1.743           ms/op
Client.existUser:existUser·p0.90      sample          2.122           ms/op
Client.existUser:existUser·p0.95      sample          2.261           ms/op
Client.existUser:existUser·p0.99      sample          2.890           ms/op
Client.existUser:existUser·p0.999     sample         26.533           ms/op
Client.existUser:existUser·p0.9999    sample         27.857           ms/op
Client.existUser:existUser·p1.00      sample         28.082           ms/op
Client.getUser                        sample  10451   3.059 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.545           ms/op
Client.getUser:getUser·p0.50          sample          2.941           ms/op
Client.getUser:getUser·p0.90          sample          3.845           ms/op
Client.getUser:getUser·p0.95          sample          4.149           ms/op
Client.getUser:getUser·p0.99          sample          5.693           ms/op
Client.getUser:getUser·p0.999         sample          8.611           ms/op
Client.getUser:getUser·p0.9999        sample          8.909           ms/op
Client.getUser:getUser·p1.00          sample          8.913           ms/op
Client.listUser                       sample   4329   7.372 ± 0.087   ms/op
Client.listUser:listUser·p0.00        sample          2.396           ms/op
Client.listUser:listUser·p0.50        sample          7.168           ms/op
Client.listUser:listUser·p0.90        sample          9.159           ms/op
Client.listUser:listUser·p0.95        sample         10.019           ms/op
Client.listUser:listUser·p0.99        sample         12.599           ms/op
Client.listUser:listUser·p0.999       sample         19.399           ms/op
Client.listUser:listUser·p0.9999      sample         19.857           ms/op
Client.listUser:listUser·p1.00        sample         19.857           ms/op
