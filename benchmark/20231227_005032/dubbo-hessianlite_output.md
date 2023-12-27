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
# Warmup Iteration   1: 2.240 ops/ms
Iteration   1: 6.093 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.093 ops/ms


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
# Warmup Iteration   1: 6.542 ops/ms
Iteration   1: 12.622 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.622 ops/ms


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
# Warmup Iteration   1: 4.447 ops/ms
Iteration   1: 9.390 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.390 ops/ms


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
# Warmup Iteration   1: 1.970 ops/ms
Iteration   1: 3.558 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.558 ops/ms


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.062 ms/op
Iteration   1: 3.213 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.213 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.028 ms/op
Iteration   1: 1.776 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.776 ms/op


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.065 ms/op
Iteration   1: 2.901 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.901 ms/op


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
# Warmup Iteration   1: 11.654 ±(99.9%) 0.188 ms/op
Iteration   1: 8.194 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.194 ms/op


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
# Warmup Iteration   1: 4.841 ±(99.9%) 0.098 ms/op
Iteration   1: 2.937 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.724 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  13.271 ms/op
                 createUser·p0.9999: 14.022 ms/op
                 createUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10896
  mean =      2.937 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 3333 
    [ 2.500,  3.750) = 6614 
    [ 3.750,  5.000) = 710 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     14.022 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 2.789 ±(99.9%) 0.055 ms/op
Iteration   1: 2.023 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   1.935 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.676 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  25.835 ms/op
                 existUser·p0.9999: 26.916 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15792
  mean =      2.023 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14232 
    [ 2.500,  5.000) = 1522 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.676 ms/op
     p(99.0000) =      3.432 ms/op
     p(99.9000) =     25.835 ms/op
     p(99.9900) =     26.916 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.087 ms/op
Iteration   1: 2.938 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.478 ms/op
                 getUser·p0.50:   2.785 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.196 ms/op
                 getUser·p0.999:  12.888 ms/op
                 getUser·p0.9999: 16.904 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11177
  mean =      2.938 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 3082 
    [ 2.500,  3.750) = 6894 
    [ 3.750,  5.000) = 1062 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.196 ms/op
     p(99.9000) =     12.888 ms/op
     p(99.9900) =     16.904 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 11.603 ±(99.9%) 0.376 ms/op
Iteration   1: 6.917 ±(99.9%) 0.084 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   6.709 ms/op
                 listUser·p0.90:   8.782 ms/op
                 listUser·p0.95:   9.508 ms/op
                 listUser·p0.99:   12.135 ms/op
                 listUser·p0.999:  18.747 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4632
  mean =      6.917 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 6 
    [ 2.500,  3.750) = 36 
    [ 3.750,  5.000) = 321 
    [ 5.000,  6.250) = 1311 
    [ 6.250,  7.500) = 1576 
    [ 7.500,  8.750) = 902 
    [ 8.750, 10.000) = 327 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.105 ms/op
     p(50.0000) =      6.709 ms/op
     p(90.0000) =      8.782 ms/op
     p(95.0000) =      9.508 ms/op
     p(99.0000) =     12.135 ms/op
     p(99.9000) =     18.747 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.093          ops/ms
Client.existUser                       thrpt         12.622          ops/ms
Client.getUser                         thrpt          9.390          ops/ms
Client.listUser                        thrpt          3.558          ops/ms
Client.createUser                       avgt          3.213           ms/op
Client.existUser                        avgt          1.776           ms/op
Client.getUser                          avgt          2.901           ms/op
Client.listUser                         avgt          8.194           ms/op
Client.createUser                     sample  10896   2.937 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.081           ms/op
Client.createUser:createUser·p0.50    sample          2.724           ms/op
Client.createUser:createUser·p0.90    sample          3.658           ms/op
Client.createUser:createUser·p0.95    sample          4.035           ms/op
Client.createUser:createUser·p0.99    sample          7.045           ms/op
Client.createUser:createUser·p0.999   sample         13.271           ms/op
Client.createUser:createUser·p0.9999  sample         14.022           ms/op
Client.createUser:createUser·p1.00    sample         14.025           ms/op
Client.existUser                      sample  15792   2.023 ± 0.030   ms/op
Client.existUser:existUser·p0.00      sample          0.794           ms/op
Client.existUser:existUser·p0.50      sample          1.935           ms/op
Client.existUser:existUser·p0.90      sample          2.499           ms/op
Client.existUser:existUser·p0.95      sample          2.676           ms/op
Client.existUser:existUser·p0.99      sample          3.432           ms/op
Client.existUser:existUser·p0.999     sample         25.835           ms/op
Client.existUser:existUser·p0.9999    sample         26.916           ms/op
Client.existUser:existUser·p1.00      sample         26.935           ms/op
Client.getUser                        sample  11177   2.938 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.478           ms/op
Client.getUser:getUser·p0.50          sample          2.785           ms/op
Client.getUser:getUser·p0.90          sample          3.772           ms/op
Client.getUser:getUser·p0.95          sample          4.035           ms/op
Client.getUser:getUser·p0.99          sample          5.196           ms/op
Client.getUser:getUser·p0.999         sample         12.888           ms/op
Client.getUser:getUser·p0.9999        sample         16.904           ms/op
Client.getUser:getUser·p1.00          sample         17.400           ms/op
Client.listUser                       sample   4632   6.917 ± 0.084   ms/op
Client.listUser:listUser·p0.00        sample          2.105           ms/op
Client.listUser:listUser·p0.50        sample          6.709           ms/op
Client.listUser:listUser·p0.90        sample          8.782           ms/op
Client.listUser:listUser·p0.95        sample          9.508           ms/op
Client.listUser:listUser·p0.99        sample         12.135           ms/op
Client.listUser:listUser·p0.999       sample         18.747           ms/op
Client.listUser:listUser·p0.9999      sample         19.104           ms/op
Client.listUser:listUser·p1.00        sample         19.104           ms/op
