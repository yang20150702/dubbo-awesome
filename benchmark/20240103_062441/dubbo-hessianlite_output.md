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
# Warmup Iteration   1: 2.208 ops/ms
Iteration   1: 6.279 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.279 ops/ms


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
# Warmup Iteration   1: 5.216 ops/ms
Iteration   1: 12.712 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.712 ops/ms


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
# Warmup Iteration   1: 4.576 ops/ms
Iteration   1: 9.259 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.259 ops/ms


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
# Warmup Iteration   1: 2.081 ops/ms
Iteration   1: 2.914 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.914 ops/ms


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.084 ms/op
Iteration   1: 2.909 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.909 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.039 ms/op
Iteration   1: 1.988 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.988 ms/op


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
# Warmup Iteration   1: 5.100 ±(99.9%) 0.063 ms/op
Iteration   1: 3.165 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.165 ms/op


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
# Warmup Iteration   1: 12.233 ±(99.9%) 0.271 ms/op
Iteration   1: 9.900 ±(99.9%) 0.105 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.900 ms/op


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
# Warmup Iteration   1: 5.411 ±(99.9%) 0.131 ms/op
Iteration   1: 3.325 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   4.177 ms/op
                 createUser·p0.95:   4.837 ms/op
                 createUser·p0.99:   12.976 ms/op
                 createUser·p0.999:  26.640 ms/op
                 createUser·p0.9999: 27.361 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9611
  mean =      3.325 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1481 
    [ 2.500,  5.000) = 7703 
    [ 5.000,  7.500) = 247 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      4.177 ms/op
     p(95.0000) =      4.837 ms/op
     p(99.0000) =     12.976 ms/op
     p(99.9000) =     26.640 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.065 ms/op
Iteration   1: 1.943 ±(99.9%) 0.095 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.228 ms/op
                 existUser·p0.95:   2.404 ms/op
                 existUser·p0.99:   2.961 ms/op
                 existUser·p0.999:  84.744 ms/op
                 existUser·p0.9999: 86.816 ms/op
                 existUser·p1.00:   86.901 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16452
  mean =      1.943 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16374 
    [ 5.000, 10.000) = 46 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 0 
    [75.000, 80.000) = 0 
    [80.000, 85.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      2.961 ms/op
     p(99.9000) =     84.744 ms/op
     p(99.9900) =     86.816 ms/op
     p(99.9990) =     86.901 ms/op
     p(99.9999) =     86.901 ms/op
    p(100.0000) =     86.901 ms/op


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.097 ms/op
Iteration   1: 3.186 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  17.628 ms/op
                 getUser·p0.9999: 19.988 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10035
  mean =      3.186 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 2302 
    [ 2.500,  3.750) = 5790 
    [ 3.750,  5.000) = 1753 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     17.628 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 13.121 ±(99.9%) 0.411 ms/op
Iteration   1: 8.438 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   2.925 ms/op
                 listUser·p0.50:   8.217 ms/op
                 listUser·p0.90:   10.612 ms/op
                 listUser·p0.95:   11.780 ms/op
                 listUser·p0.99:   15.350 ms/op
                 listUser·p0.999:  25.852 ms/op
                 listUser·p0.9999: 29.032 ms/op
                 listUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3782
  mean =      8.438 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 68 
    [ 5.000,  7.500) = 1157 
    [ 7.500, 10.000) = 1963 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.925 ms/op
     p(50.0000) =      8.217 ms/op
     p(90.0000) =     10.612 ms/op
     p(95.0000) =     11.780 ms/op
     p(99.0000) =     15.350 ms/op
     p(99.9000) =     25.852 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.279          ops/ms
Client.existUser                       thrpt         12.712          ops/ms
Client.getUser                         thrpt          9.259          ops/ms
Client.listUser                        thrpt          2.914          ops/ms
Client.createUser                       avgt          2.909           ms/op
Client.existUser                        avgt          1.988           ms/op
Client.getUser                          avgt          3.165           ms/op
Client.listUser                         avgt          9.900           ms/op
Client.createUser                     sample   9611   3.325 ± 0.069   ms/op
Client.createUser:createUser·p0.00    sample          1.141           ms/op
Client.createUser:createUser·p0.50    sample          2.974           ms/op
Client.createUser:createUser·p0.90    sample          4.177           ms/op
Client.createUser:createUser·p0.95    sample          4.837           ms/op
Client.createUser:createUser·p0.99    sample         12.976           ms/op
Client.createUser:createUser·p0.999   sample         26.640           ms/op
Client.createUser:createUser·p0.9999  sample         27.361           ms/op
Client.createUser:createUser·p1.00    sample         27.361           ms/op
Client.existUser                      sample  16452   1.943 ± 0.095   ms/op
Client.existUser:existUser·p0.00      sample          0.695           ms/op
Client.existUser:existUser·p0.50      sample          1.747           ms/op
Client.existUser:existUser·p0.90      sample          2.228           ms/op
Client.existUser:existUser·p0.95      sample          2.404           ms/op
Client.existUser:existUser·p0.99      sample          2.961           ms/op
Client.existUser:existUser·p0.999     sample         84.744           ms/op
Client.existUser:existUser·p0.9999    sample         86.816           ms/op
Client.existUser:existUser·p1.00      sample         86.901           ms/op
Client.getUser                        sample  10035   3.186 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          0.740           ms/op
Client.getUser:getUser·p0.50          sample          3.158           ms/op
Client.getUser:getUser·p0.90          sample          4.018           ms/op
Client.getUser:getUser·p0.95          sample          4.268           ms/op
Client.getUser:getUser·p0.99          sample          5.349           ms/op
Client.getUser:getUser·p0.999         sample         17.628           ms/op
Client.getUser:getUser·p0.9999        sample         19.988           ms/op
Client.getUser:getUser·p1.00          sample         19.988           ms/op
Client.listUser                       sample   3782   8.438 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          2.925           ms/op
Client.listUser:listUser·p0.50        sample          8.217           ms/op
Client.listUser:listUser·p0.90        sample         10.612           ms/op
Client.listUser:listUser·p0.95        sample         11.780           ms/op
Client.listUser:listUser·p0.99        sample         15.350           ms/op
Client.listUser:listUser·p0.999       sample         25.852           ms/op
Client.listUser:listUser·p0.9999      sample         29.032           ms/op
Client.listUser:listUser·p1.00        sample         29.032           ms/op
