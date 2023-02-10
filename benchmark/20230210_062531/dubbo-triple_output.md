# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.364 ops/ms
# Warmup Iteration   2: 4.667 ops/ms
# Warmup Iteration   3: 9.373 ops/ms
Iteration   1: 9.573 ops/ms
Iteration   2: 9.918 ops/ms
Iteration   3: 10.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.857 ±(99.9%) 4.726 ops/ms [Average]
  (min, avg, max) = (9.573, 9.857, 10.080), stdev = 0.259
  CI (99.9%): [5.131, 14.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.521 ops/ms
# Warmup Iteration   2: 9.175 ops/ms
# Warmup Iteration   3: 10.342 ops/ms
Iteration   1: 10.331 ops/ms
Iteration   2: 10.392 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.466 ±(99.9%) 3.355 ops/ms [Average]
  (min, avg, max) = (10.331, 10.466, 10.676), stdev = 0.184
  CI (99.9%): [7.111, 13.821] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.807 ops/ms
# Warmup Iteration   2: 9.362 ops/ms
# Warmup Iteration   3: 10.103 ops/ms
Iteration   1: 10.223 ops/ms
Iteration   2: 10.602 ops/ms
Iteration   3: 9.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.246 ±(99.9%) 6.288 ops/ms [Average]
  (min, avg, max) = (9.914, 10.246, 10.602), stdev = 0.345
  CI (99.9%): [3.958, 16.534] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.375 ops/ms
# Warmup Iteration   2: 7.777 ops/ms
# Warmup Iteration   3: 8.482 ops/ms
Iteration   1: 8.538 ops/ms
Iteration   2: 8.780 ops/ms
Iteration   3: 8.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.702 ±(99.9%) 2.603 ops/ms [Average]
  (min, avg, max) = (8.538, 8.702, 8.790), stdev = 0.143
  CI (99.9%): [6.099, 11.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.308 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.006 ms/op
Iteration   1: 3.139 ±(99.9%) 0.003 ms/op
Iteration   2: 3.208 ±(99.9%) 0.005 ms/op
Iteration   3: 3.266 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.204 ±(99.9%) 1.162 ms/op [Average]
  (min, avg, max) = (3.139, 3.204, 3.266), stdev = 0.064
  CI (99.9%): [2.042, 4.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.006 ms/op
Iteration   1: 3.085 ±(99.9%) 0.001 ms/op
Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
Iteration   3: 3.102 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.086 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.072, 3.086, 3.102), stdev = 0.015
  CI (99.9%): [2.817, 3.355] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.959 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.003 ms/op
Iteration   1: 3.158 ±(99.9%) 0.003 ms/op
Iteration   2: 3.250 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.169 ±(99.9%) 1.399 ms/op [Average]
  (min, avg, max) = (3.098, 3.169, 3.250), stdev = 0.077
  CI (99.9%): [1.769, 4.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.616 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.006 ms/op
Iteration   1: 3.712 ±(99.9%) 0.008 ms/op
Iteration   2: 3.729 ±(99.9%) 0.010 ms/op
Iteration   3: 3.723 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (3.712, 3.722, 3.729), stdev = 0.009
  CI (99.9%): [3.560, 3.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.535 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.391 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  10.267 ms/op
                 createUser·p0.9999: 19.416 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  17.510 ms/op
                 createUser·p0.9999: 25.014 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  15.560 ms/op
                 createUser·p0.9999: 24.209 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304993
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14410 
    [ 2.500,  5.000) = 286434 
    [ 5.000,  7.500) = 3148 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     24.232 ms/op
     p(99.9990) =     25.779 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.751 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
Iteration   1: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   4.784 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 18.028 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 23.509 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315970
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27980 
    [ 2.500,  5.000) = 283840 
    [ 5.000,  7.500) = 3327 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.236 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     12.241 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     24.043 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.499 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.009 ms/op
Iteration   1: 3.189 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  15.896 ms/op
                 getUser·p0.9999: 20.114 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 25.756 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 19.065 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305013
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12135 
    [ 2.500,  5.000) = 286388 
    [ 5.000,  7.500) = 5594 
    [ 7.500, 10.000) = 516 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     13.693 ms/op
     p(99.9900) =     24.396 ms/op
     p(99.9990) =     26.177 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.276 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.011 ms/op
Iteration   1: 3.724 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.202 ms/op
                 listUser·p0.9999: 25.369 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 3.756 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.155 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 3.675 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.861 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258045
  mean =      3.718 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 250554 
    [ 5.000,  7.500) = 5622 
    [ 7.500, 10.000) = 1058 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.968 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     23.579 ms/op
     p(99.9990) =     25.680 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.857 ± 4.726  ops/ms
ClientPb.existUser                       thrpt       3  10.466 ± 3.355  ops/ms
ClientPb.getUser                         thrpt       3  10.246 ± 6.288  ops/ms
ClientPb.listUser                        thrpt       3   8.702 ± 2.603  ops/ms
ClientPb.createUser                       avgt       3   3.204 ± 1.162   ms/op
ClientPb.existUser                        avgt       3   3.086 ± 0.269   ms/op
ClientPb.getUser                          avgt       3   3.169 ± 1.399   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 0.161   ms/op
ClientPb.createUser                     sample  304993   3.145 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.486           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.024           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.232           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  315970   3.036 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.231           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.241           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.708           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.347           ms/op
ClientPb.getUser                        sample  305013   3.143 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.449           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.693           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.396           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.477           ms/op
ClientPb.listUser                       sample  258045   3.718 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.348           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.564           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.968           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.579           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.018           ms/op
