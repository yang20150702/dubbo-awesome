# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.843 ops/ms
# Warmup Iteration   2: 5.229 ops/ms
# Warmup Iteration   3: 8.258 ops/ms
Iteration   1: 9.113 ops/ms
Iteration   2: 9.126 ops/ms
Iteration   3: 9.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.185 ±(99.9%) 2.066 ops/ms [Average]
  (min, avg, max) = (9.113, 9.185, 9.316), stdev = 0.113
  CI (99.9%): [7.119, 11.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.679 ops/ms
# Warmup Iteration   2: 7.932 ops/ms
# Warmup Iteration   3: 9.173 ops/ms
Iteration   1: 9.398 ops/ms
Iteration   2: 9.258 ops/ms
Iteration   3: 9.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.413 ±(99.9%) 2.982 ops/ms [Average]
  (min, avg, max) = (9.258, 9.413, 9.584), stdev = 0.163
  CI (99.9%): [6.431, 12.396] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.809 ops/ms
# Warmup Iteration   2: 7.726 ops/ms
# Warmup Iteration   3: 8.748 ops/ms
Iteration   1: 8.847 ops/ms
Iteration   2: 8.973 ops/ms
Iteration   3: 8.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.840 ±(99.9%) 2.473 ops/ms [Average]
  (min, avg, max) = (8.702, 8.840, 8.973), stdev = 0.136
  CI (99.9%): [6.368, 11.313] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.400 ops/ms
# Warmup Iteration   2: 7.009 ops/ms
# Warmup Iteration   3: 7.397 ops/ms
Iteration   1: 7.615 ops/ms
Iteration   2: 7.723 ops/ms
Iteration   3: 7.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.656 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (7.615, 7.656, 7.723), stdev = 0.058
  CI (99.9%): [6.592, 8.720] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.035 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.007 ms/op
Iteration   1: 3.602 ±(99.9%) 0.003 ms/op
Iteration   2: 3.558 ±(99.9%) 0.006 ms/op
Iteration   3: 3.495 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.552 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.495, 3.552, 3.602), stdev = 0.054
  CI (99.9%): [2.568, 4.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.090 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.005 ms/op
Iteration   1: 3.447 ±(99.9%) 0.006 ms/op
Iteration   2: 3.422 ±(99.9%) 0.006 ms/op
Iteration   3: 3.395 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.421 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.395, 3.421, 3.447), stdev = 0.026
  CI (99.9%): [2.950, 3.893] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.930 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.006 ms/op
Iteration   1: 3.569 ±(99.9%) 0.007 ms/op
Iteration   2: 3.547 ±(99.9%) 0.004 ms/op
Iteration   3: 3.606 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.574 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.547, 3.574, 3.606), stdev = 0.030
  CI (99.9%): [3.033, 4.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.025 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.452 ±(99.9%) 0.006 ms/op
Iteration   1: 4.218 ±(99.9%) 0.009 ms/op
Iteration   2: 4.194 ±(99.9%) 0.011 ms/op
Iteration   3: 4.166 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.192 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (4.166, 4.192, 4.218), stdev = 0.026
  CI (99.9%): [3.717, 4.668] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 12.017 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.016 ms/op
Iteration   1: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.744 ms/op
                 createUser·p0.999:  18.279 ms/op
                 createUser·p0.9999: 22.869 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.528 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.548 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  23.028 ms/op
                 createUser·p0.9999: 28.704 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271970
  mean =      3.530 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4516 
    [ 2.500,  5.000) = 259251 
    [ 5.000,  7.500) = 6333 
    [ 7.500, 10.000) = 1271 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.364 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.011 ms/op
Iteration   1: 3.510 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  13.271 ms/op
                 existUser·p0.9999: 29.357 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   2: 3.443 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  22.906 ms/op
                 existUser·p0.9999: 27.660 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.512 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.789 ms/op
                 existUser·p0.999:  25.068 ms/op
                 existUser·p0.9999: 30.144 ms/op
                 existUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274977
  mean =      3.488 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3667 
    [ 2.500,  5.000) = 260382 
    [ 5.000,  7.500) = 9126 
    [ 7.500, 10.000) = 1077 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     29.458 ms/op
     p(99.9990) =     30.958 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.488 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.013 ms/op
Iteration   1: 3.593 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.780 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   7.823 ms/op
                 getUser·p0.999:  20.840 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.577 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.626 ms/op
                 getUser·p0.999:  21.041 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 3.639 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.046 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  11.190 ms/op
                 getUser·p0.9999: 30.894 ms/op
                 getUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266385
  mean =      3.603 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4938 
    [ 2.500,  5.000) = 248713 
    [ 5.000,  7.500) = 10164 
    [ 7.500, 10.000) = 1738 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.780 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     30.027 ms/op
     p(99.9990) =     31.283 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.369 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.769 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.443 ±(99.9%) 0.016 ms/op
Iteration   1: 4.260 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  21.791 ms/op
                 listUser·p0.9999: 26.558 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 4.443 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  17.006 ms/op
                 listUser·p0.9999: 19.818 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.405 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 21.044 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 219659
  mean =      4.368 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 205748 
    [ 5.000,  7.500) = 9400 
    [ 7.500, 10.000) = 3308 
    [10.000, 12.500) = 634 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     17.673 ms/op
     p(99.9900) =     25.298 ms/op
     p(99.9990) =     27.512 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.185 ± 2.066  ops/ms
ClientPb.existUser                       thrpt       3   9.413 ± 2.982  ops/ms
ClientPb.getUser                         thrpt       3   8.840 ± 2.473  ops/ms
ClientPb.listUser                        thrpt       3   7.656 ± 1.064  ops/ms
ClientPb.createUser                       avgt       3   3.552 ± 0.984   ms/op
ClientPb.existUser                        avgt       3   3.421 ± 0.472   ms/op
ClientPb.getUser                          avgt       3   3.574 ± 0.541   ms/op
ClientPb.listUser                         avgt       3   4.192 ± 0.476   ms/op
ClientPb.createUser                     sample  271970   3.530 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.053           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.018           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.014           ms/op
ClientPb.existUser                      sample  274977   3.488 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.278           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.914           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.458           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.162           ms/op
ClientPb.getUser                        sample  266385   3.603 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.780           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.882           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.447           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.464           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.027           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.785           ms/op
ClientPb.listUser                       sample  219659   4.368 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.538           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.700           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.673           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.298           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
