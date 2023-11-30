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
# Warmup Iteration   1: 2.248 ops/ms
Iteration   1: 6.020 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.020 ops/ms


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
# Warmup Iteration   1: 5.520 ops/ms
Iteration   1: 13.147 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.147 ops/ms


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
# Warmup Iteration   1: 4.219 ops/ms
Iteration   1: 7.927 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.927 ops/ms


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
# Warmup Iteration   1: 1.945 ops/ms
Iteration   1: 3.432 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.432 ops/ms


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
# Warmup Iteration   1: 5.638 ±(99.9%) 0.086 ms/op
Iteration   1: 3.384 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.384 ms/op


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
# Warmup Iteration   1: 3.113 ±(99.9%) 0.036 ms/op
Iteration   1: 1.823 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.823 ms/op


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
# Warmup Iteration   1: 4.547 ±(99.9%) 0.052 ms/op
Iteration   1: 2.881 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.881 ms/op


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
# Warmup Iteration   1: 11.377 ±(99.9%) 0.170 ms/op
Iteration   1: 8.337 ±(99.9%) 0.111 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.337 ms/op


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
# Warmup Iteration   1: 4.942 ±(99.9%) 0.116 ms/op
Iteration   1: 2.763 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 11.857 ms/op
                 createUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11583
  mean =      2.763 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 4165 
    [ 2.500,  3.750) = 6828 
    [ 3.750,  5.000) = 408 
    [ 5.000,  6.250) = 115 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      2.687 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     11.551 ms/op
     p(99.9900) =     11.857 ms/op
     p(99.9990) =     11.862 ms/op
     p(99.9999) =     11.862 ms/op
    p(100.0000) =     11.862 ms/op


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
# Warmup Iteration   1: 2.943 ±(99.9%) 0.064 ms/op
Iteration   1: 2.025 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   1.985 ms/op
                 existUser·p0.90:   2.642 ms/op
                 existUser·p0.95:   2.810 ms/op
                 existUser·p0.99:   3.220 ms/op
                 existUser·p0.999:  5.399 ms/op
                 existUser·p0.9999: 5.589 ms/op
                 existUser·p1.00:   5.603 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15790
  mean =      2.025 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 101 
    [1.000, 1.500) = 2336 
    [1.500, 2.000) = 5699 
    [2.000, 2.500) = 5020 
    [2.500, 3.000) = 2270 
    [3.000, 3.500) = 284 
    [3.500, 4.000) = 34 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 5 
    [5.000, 5.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      3.220 ms/op
     p(99.9000) =      5.399 ms/op
     p(99.9900) =      5.589 ms/op
     p(99.9990) =      5.603 ms/op
     p(99.9999) =      5.603 ms/op
    p(100.0000) =      5.603 ms/op


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
# Warmup Iteration   1: 4.825 ±(99.9%) 0.145 ms/op
Iteration   1: 2.732 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  6.723 ms/op
                 getUser·p0.9999: 7.182 ms/op
                 getUser·p1.00:   7.209 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11757
  mean =      2.732 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 30 
    [1.500, 2.000) = 472 
    [2.000, 2.500) = 4165 
    [2.500, 3.000) = 4086 
    [3.000, 3.500) = 2107 
    [3.500, 4.000) = 463 
    [4.000, 4.500) = 203 
    [4.500, 5.000) = 144 
    [5.000, 5.500) = 33 
    [5.500, 6.000) = 8 
    [6.000, 6.500) = 32 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      6.723 ms/op
     p(99.9900) =      7.182 ms/op
     p(99.9990) =      7.209 ms/op
     p(99.9999) =      7.209 ms/op
    p(100.0000) =      7.209 ms/op


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
# Warmup Iteration   1: 11.005 ±(99.9%) 0.362 ms/op
Iteration   1: 7.412 ±(99.9%) 0.172 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   6.906 ms/op
                 listUser·p0.90:   9.247 ms/op
                 listUser·p0.95:   10.289 ms/op
                 listUser·p0.99:   20.405 ms/op
                 listUser·p0.999:  42.489 ms/op
                 listUser·p0.9999: 53.281 ms/op
                 listUser·p1.00:   53.281 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4305
  mean =      7.412 ±(99.9%) 0.172 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 271 
    [ 5.000, 10.000) = 3767 
    [10.000, 15.000) = 194 
    [15.000, 20.000) = 29 
    [20.000, 25.000) = 12 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 14 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.241 ms/op
     p(50.0000) =      6.906 ms/op
     p(90.0000) =      9.247 ms/op
     p(95.0000) =     10.289 ms/op
     p(99.0000) =     20.405 ms/op
     p(99.9000) =     42.489 ms/op
     p(99.9900) =     53.281 ms/op
     p(99.9990) =     53.281 ms/op
     p(99.9999) =     53.281 ms/op
    p(100.0000) =     53.281 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.020          ops/ms
Client.existUser                       thrpt         13.147          ops/ms
Client.getUser                         thrpt          7.927          ops/ms
Client.listUser                        thrpt          3.432          ops/ms
Client.createUser                       avgt          3.384           ms/op
Client.existUser                        avgt          1.823           ms/op
Client.getUser                          avgt          2.881           ms/op
Client.listUser                         avgt          8.337           ms/op
Client.createUser                     sample  11583   2.763 ± 0.023   ms/op
Client.createUser:createUser·p0.00    sample          1.014           ms/op
Client.createUser:createUser·p0.50    sample          2.687           ms/op
Client.createUser:createUser·p0.90    sample          3.363           ms/op
Client.createUser:createUser·p0.95    sample          3.752           ms/op
Client.createUser:createUser·p0.99    sample          5.562           ms/op
Client.createUser:createUser·p0.999   sample         11.551           ms/op
Client.createUser:createUser·p0.9999  sample         11.857           ms/op
Client.createUser:createUser·p1.00    sample         11.862           ms/op
Client.existUser                      sample  15790   2.025 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.743           ms/op
Client.existUser:existUser·p0.50      sample          1.985           ms/op
Client.existUser:existUser·p0.90      sample          2.642           ms/op
Client.existUser:existUser·p0.95      sample          2.810           ms/op
Client.existUser:existUser·p0.99      sample          3.220           ms/op
Client.existUser:existUser·p0.999     sample          5.399           ms/op
Client.existUser:existUser·p0.9999    sample          5.589           ms/op
Client.existUser:existUser·p1.00      sample          5.603           ms/op
Client.getUser                        sample  11757   2.732 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.970           ms/op
Client.getUser:getUser·p0.50          sample          2.626           ms/op
Client.getUser:getUser·p0.90          sample          3.424           ms/op
Client.getUser:getUser·p0.95          sample          3.740           ms/op
Client.getUser:getUser·p0.99          sample          4.833           ms/op
Client.getUser:getUser·p0.999         sample          6.723           ms/op
Client.getUser:getUser·p0.9999        sample          7.182           ms/op
Client.getUser:getUser·p1.00          sample          7.209           ms/op
Client.listUser                       sample   4305   7.412 ± 0.172   ms/op
Client.listUser:listUser·p0.00        sample          2.241           ms/op
Client.listUser:listUser·p0.50        sample          6.906           ms/op
Client.listUser:listUser·p0.90        sample          9.247           ms/op
Client.listUser:listUser·p0.95        sample         10.289           ms/op
Client.listUser:listUser·p0.99        sample         20.405           ms/op
Client.listUser:listUser·p0.999       sample         42.489           ms/op
Client.listUser:listUser·p0.9999      sample         53.281           ms/op
Client.listUser:listUser·p1.00        sample         53.281           ms/op
