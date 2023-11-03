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
# Warmup Iteration   1: 2.260 ops/ms
Iteration   1: 6.010 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.010 ops/ms


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
# Warmup Iteration   1: 5.674 ops/ms
Iteration   1: 14.197 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.197 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.439 ops/ms
Iteration   1: 9.733 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.733 ops/ms


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
# Warmup Iteration   1: 2.203 ops/ms
Iteration   1: 3.759 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.759 ops/ms


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
# Warmup Iteration   1: 5.003 ±(99.9%) 0.098 ms/op
Iteration   1: 3.023 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.023 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.040 ms/op
Iteration   1: 1.934 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.934 ms/op


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.053 ms/op
Iteration   1: 3.078 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.078 ms/op


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
# Warmup Iteration   1: 10.903 ±(99.9%) 0.225 ms/op
Iteration   1: 8.674 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.674 ms/op


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
# Warmup Iteration   1: 4.737 ±(99.9%) 0.108 ms/op
Iteration   1: 3.495 ±(99.9%) 0.153 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  78.730 ms/op
                 createUser·p0.9999: 79.561 ms/op
                 createUser·p1.00:   79.561 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9333
  mean =      3.495 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9093 
    [ 5.000, 10.000) = 156 
    [10.000, 15.000) = 52 
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

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     78.730 ms/op
     p(99.9900) =     79.561 ms/op
     p(99.9990) =     79.561 ms/op
     p(99.9999) =     79.561 ms/op
    p(100.0000) =     79.561 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.131 ms/op
Iteration   1: 1.741 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.476 ms/op
                 existUser·p0.50:   1.606 ms/op
                 existUser·p0.90:   2.091 ms/op
                 existUser·p0.95:   2.257 ms/op
                 existUser·p0.99:   3.039 ms/op
                 existUser·p0.999:  29.852 ms/op
                 existUser·p0.9999: 30.114 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18341
  mean =      1.741 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17935 
    [ 2.500,  5.000) = 334 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      1.606 ms/op
     p(90.0000) =      2.091 ms/op
     p(95.0000) =      2.257 ms/op
     p(99.0000) =      3.039 ms/op
     p(99.9000) =     29.852 ms/op
     p(99.9900) =     30.114 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.097 ms/op
Iteration   1: 3.054 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  13.533 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10485
  mean =      3.054 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 2271 
    [ 2.500,  3.750) = 6786 
    [ 3.750,  5.000) = 1217 
    [ 5.000,  6.250) = 152 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


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
# Warmup Iteration   1: 11.158 ±(99.9%) 0.350 ms/op
Iteration   1: 8.220 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   2.982 ms/op
                 listUser·p0.50:   7.823 ms/op
                 listUser·p0.90:   10.764 ms/op
                 listUser·p0.95:   11.804 ms/op
                 listUser·p0.99:   17.048 ms/op
                 listUser·p0.999:  20.415 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3990
  mean =      8.220 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 142 
    [ 5.000,  7.500) = 1550 
    [ 7.500, 10.000) = 1592 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.982 ms/op
     p(50.0000) =      7.823 ms/op
     p(90.0000) =     10.764 ms/op
     p(95.0000) =     11.804 ms/op
     p(99.0000) =     17.048 ms/op
     p(99.9000) =     20.415 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.010          ops/ms
Client.existUser                       thrpt         14.197          ops/ms
Client.getUser                         thrpt          9.733          ops/ms
Client.listUser                        thrpt          3.759          ops/ms
Client.createUser                       avgt          3.023           ms/op
Client.existUser                        avgt          1.934           ms/op
Client.getUser                          avgt          3.078           ms/op
Client.listUser                         avgt          8.674           ms/op
Client.createUser                     sample   9333   3.495 ± 0.153   ms/op
Client.createUser:createUser·p0.00    sample          1.225           ms/op
Client.createUser:createUser·p0.50    sample          2.978           ms/op
Client.createUser:createUser·p0.90    sample          4.186           ms/op
Client.createUser:createUser·p0.95    sample          4.555           ms/op
Client.createUser:createUser·p0.99    sample          9.617           ms/op
Client.createUser:createUser·p0.999   sample         78.730           ms/op
Client.createUser:createUser·p0.9999  sample         79.561           ms/op
Client.createUser:createUser·p1.00    sample         79.561           ms/op
Client.existUser                      sample  18341   1.741 ± 0.031   ms/op
Client.existUser:existUser·p0.00      sample          0.476           ms/op
Client.existUser:existUser·p0.50      sample          1.606           ms/op
Client.existUser:existUser·p0.90      sample          2.091           ms/op
Client.existUser:existUser·p0.95      sample          2.257           ms/op
Client.existUser:existUser·p0.99      sample          3.039           ms/op
Client.existUser:existUser·p0.999     sample         29.852           ms/op
Client.existUser:existUser·p0.9999    sample         30.114           ms/op
Client.existUser:existUser·p1.00      sample         30.114           ms/op
Client.getUser                        sample  10485   3.054 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          0.680           ms/op
Client.getUser:getUser·p0.50          sample          2.904           ms/op
Client.getUser:getUser·p0.90          sample          3.867           ms/op
Client.getUser:getUser·p0.95          sample          4.211           ms/op
Client.getUser:getUser·p0.99          sample          5.333           ms/op
Client.getUser:getUser·p0.999         sample         13.533           ms/op
Client.getUser:getUser·p0.9999        sample         13.599           ms/op
Client.getUser:getUser·p1.00          sample         13.599           ms/op
Client.listUser                       sample   3990   8.220 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          2.982           ms/op
Client.listUser:listUser·p0.50        sample          7.823           ms/op
Client.listUser:listUser·p0.90        sample         10.764           ms/op
Client.listUser:listUser·p0.95        sample         11.804           ms/op
Client.listUser:listUser·p0.99        sample         17.048           ms/op
Client.listUser:listUser·p0.999       sample         20.415           ms/op
Client.listUser:listUser·p0.9999      sample         21.201           ms/op
Client.listUser:listUser·p1.00        sample         21.201           ms/op
